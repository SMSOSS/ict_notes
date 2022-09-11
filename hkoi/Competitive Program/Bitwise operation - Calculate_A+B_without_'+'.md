# First, what is bitwise opeeration? #
doing operation with binary numbers
## AND (& in C++) ## 
```
a & b // return 1 when both is 1
1 & 1 = 1
0 & 1 = 0
0 & 0 = 0
```
### Can be use to find odd number! ###
```
int num = 7;
if(num&1) cout << "odd";
else cout << "even";

//output = odd
```
Explanation:
7 = 111(BIN), 1 = (001)
  111 & 001 == 001 -> true;  

## OR ( | in C++) ##
```
a | b // return 1 when either one or both is 1
1 | 1 = 1;
1 | 0 = 1;
0 | 0 = 1;
```

### Can add number with OR, if no carry involve ###
In two numbers where no binary digit in the same position is both 1;
eg. 1010 and 0101, 0001 or 0100
```
1010 | 0101 = 1111 = 15
10 + 5 = 15

0001 | 0100 = 0101 = 9
1 + 8 = 9
```
But for 1100 and 0110
```
1100 | 0110 = 1110 = 14
12 + 6 = 18 != 14
**Because Coeff. of 2^3 is both 1**
```

## XOR (^ in C++) ## 
The result of XOR is 1 if the two bits are different. (ie 1^0 = 0);

## Bit shift ##
- ``` << (left shift) ``` and  ``` >> (right shift) ```
- same as ```cout <<``` and ```cin >>```;

```
int a = 11101; //in binary
int b = 11101; 

a = a << 1;
b = b >> 1;

// a is now 111010, with an extra bit '0' on the back
// b is now 1110, with the diappear bit '1'
```

- Therefore, bit shift left can be interprete as \*2 (ie a << N == a\***2tothepowerN**)
- Therefore, bit shift right can be interprete as \2 (ie a >> N == floor(a\***2tothepower(-N)**))
- *note: floor meaning round down in c++*


# How to add two decimal number with bitwise operator only? #
In HKOI task D100, it asked you to output A + B, you think it is too simple and looking for something more challenging 
- As we know, OR can sum up non-carrying addition, how about there is carry?
- There is a carry only when the **Both Coeff. of 2^(n) is 1 **

|A| 1100 |
|-|------|
|B| 0110 |
|&| 0100 |

- Therefore, to add two integer, you just need **OR to calculate non-carrying sum** and **AND to calculate the carrying part**
- Fore example we want 12 + 6

| a | b | sum(OR) | carry(AND) |
|---|---|---------|------------|
| 1 | 0 |    1    |      0     |
| 1 | 1 |    1    |      1     |
| 0 | 1 |    1    |      0     |
| 0 | 0 |    0    |      0     |

-But then how can we add the carry to the sum? We can bit shift left it to bring the digit forward! Then do the addition again

| sum(OR) | carry << 1 | 'sum(OR) | 'carry(AND) |
|---------|------------|----------|-------------|
|    1    |      1     |    1     |      1      |
|    1    |      0     |    1     |      0      |
|    1    |      0     |    1     |      0      |
|    0    |      0     |    0     |      0      |

| sum(OR) | carry << 1 | 'sum(OR) | 'carry(AND) |
|---------|------------|----------|-------------|
|    0    |      1     |    1     |      0      |
|    1    |      0     |    1     |      0      |
|    1    |      0     |    1     |      0      |
|    1    |      0     |    1     |      0      |
|    0    |      0     |    0     |      0      |

Hey the carry now is 0 and the sum is the final answer!

## C++ Scource code ##

```
#include <bits/stdc++.h>
using namespace std;
int bitwise_add(int a, int b)
{
  if(b == 0) return a; // a is the answer

  return bitwise_add(a^b, (a&b)<<1); // a^b is sum, (a&b) << 1 is carry
}

int main() {
  int a, b;
  cin >> a >> b;

  cout << bitwise_add(a, b);

  return 0;
}

```
