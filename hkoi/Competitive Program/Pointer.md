# Pointer #

## use '&' to get the address of that var ##
```
int x ;
cout << &x; // output address of x
```

## Use '*' to declare a pointer var ##
```
int x;
int *ptr;
ptr = &x; // address of x is assigned to ptr 
```

## Use '*' to access the value stored in address ##
```
int x ; 
int *ptr = &x; // address of x is assigned to ptr
*ptr = 20; // change value stored in address to 20
```
