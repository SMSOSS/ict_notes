# hkoi tutorial #1 #

## linear search ##

Ex : 100 int find 17 -> for loop

- find from first int 
- need long time , low efficiency 

```
// c++

found = 0 ;
while(i<100 and found == 0){
    if(same){
        found =1 ;
    }else{
        i++ ; 
    }
}

```

## binary search ##
- requirement : sorted data ( 1 , 3 , 7 , 11)
- find from middle (larger / smaller ->　decrease search range)
- no need long time , high efficiency
- D801 [link](https://judge.hkoi.org/task/D801)
- log n 

```
// c++

found = 0 ; 
i = n/2 ; 

while(found = 0){
    if(true){
        found = 1 ;
    }elseif ( s > a[i]){
        i = i+n/2 ;     
    }else if (s< a[i]){
        i = 1+i/2 ; 
    }
}

```

## selection sort ##
- find from smallest to largest 
- need to run n^2 times to find -> low efficiency

## insertion sort ##
- find suitable space and insert 
- move other number to insert
- need to run  n^2 times to find (worst case) -> low efficiency

## bubble sort ##
- move largest to right each time 
- need to run n^2 times to find -> low efficiency
- D802 [link](https://judge.hkoi.org/task/D802) , D803 [link](https://judge.hkoi.org/task/D803) 

``` 
// c++ 

if(order==0){ //ascending
    for(int i = 0 ; i<=value-1 ; i++){
      for(int j = 0 ; j<=value-1 ; j++){
        if(table[j] > table[j+1]){
          long int temp = table[j+1];
          table[j+1] = table[j];
          table[j] = temp;
          move++ ; 
        }
      }
    }
  }else{ //descending 
    for(int i = 0 ; i<=value-1 ; i++){
      for(int j = 0 ; j<value-1 ; j++){
        if(table[j] < table[j+1]){
          long int temp = table[j+1];
          table[j+1] = table[j];
          table[j] = temp;
          move++ ; 
        }
      }
    }
  }
```

## couting sort ##
- create array -> record how many times appear 
- only need to run n times to run 
- waste unused space , can't open large array -> use space to exchange time 

```
// c++ 
for (int i = 0 ; i <1000 ; i++){
    for (int j = 0 ; j < a[i] ; j++){

    }
}
```

## qucik sort ##
- choose last one int to be middle 
- larger -> left , smaller -> right 
- continue choose one int to be middle 
- need to run log n * n times -> high efficiency
- D807 [link](https://judge.hkoi.org/task/D807) , D808 [link](https://judge.hkoi.org/task/D808) 

## random sort ##
- quick sort but randomly choose int 

made by tkt0506 
