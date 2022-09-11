# What is header file? #

A external source file that you can use it after including it!

# std_library #

- A **main component** of the c++ language.
- providing large variety of I/O, maths function, containers and data structures
- 
## include <header_file.h> ##
```
#include <bits/stdc++.h>
using namespace std;
```

"namespace" is create to classify function with same name in a program

# Useful container #

## vector\<type> ##
  
simply saying, it is a array which u doesn't need to assign a size to it
For example
```
vector<int> nums{1, 2, 3, 4, 5, 6};
nums.push_back(10);
for(int i = 0; i < nums.size(); i++) cout << nums[i] << " ";
```
- this would output ```1 2 3 4 5 6 10; ```
- push_back to add elements to the back

## stack\<type> ##

Is a build in stack container, first-in-first-out

```
stack<int> s;
s.push(1); //current = {1}
s.push(7); //current = {1, 7}
s.push(3); current = {1, 7, 3}
cout << s.top(); // output = 3, current = {1, 7, 3}
s.pop() //current = {1, 7}
s.pop() //current = {1}
cout << s.size(); //output = 1;
```
simple

## queue\<type> ##
similar to stack but perform first-in-last-out
```
queue<int> s;
s.push(1); //current = {1}
s.push(7); //current = {1, 7}
s.push(3); current = {1, 7, 3}
cout << s.top(); // output = 3, current = {1, 7, 3}
s.pop() //current = {7, 3}
s.pop() //current = {3}
cout << s.size(); //output = 1;
```
easy

## map\<type, type> ##
- map include "keys" and "values", they are in "pair<key, value>"
- For example
```
map<string, int> score;
score[tkt] = 85;
score[6y] = 85;
score[left] = 30;
cout << score[left]; //output = 30
```
straightforward 

# Function in STL #
-There is a bunch of cheating function in STL
-Recommended not to use these functions before you understand how it works, otherwise you will miss a lot of chances to learn.

## max()/min() ##
```
cout << max(10, 20); // 20
cout << min(10, 20); // 10

## sort() ##
```
int nums[10] = {10, 1, 4, 6, 2, 7, 3, 8, 9, 5};
sort(nums, nums+10);
//output nums you will get 1 2 3 4 5 6 7 8 9 10
```
It is basically a quicksort, you can add bool function in it,
For example,
```
bool cmp(int a, int b)
{
return a > b;
}
sort(nums, nums+10, cmp) // it will then sort in descending 
```

# For more others elements in STL #
English: https://www.geeksforgeeks.org/the-c-standard-template-library-stl/
