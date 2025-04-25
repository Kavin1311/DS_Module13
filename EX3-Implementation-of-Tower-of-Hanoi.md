![image](https://github.com/user-attachments/assets/d3d49b78-612a-457b-84f9-54dfdd1c31e6)# EX3 Implementation of Tower of Hanoi
## DATE: 24/05/2025
## AIM:
To write a C program to implement Tower of Hanoi

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
Program to implement Tower of Hanoi
Developed by: T.KAVINAJAI
RegisterNumber: 212223100020
```
#include<stdio.h>
void TOH(int n,char x,char y,char z)
{
   if(n>0)
   {
      TOH(n-1,x,z,y);
      printf("%c to %c",x,y);
      printf("\n");
      TOH(n-1,z,y,x);
   }
}
```  
*/
```

## Output:
![image](https://github.com/user-attachments/assets/969b7c0b-a9d9-4046-8a99-5b9256b1b682)



## Result:
Thus, the C program to implement Tower of Hanoi using recursion is implemented successfully.
