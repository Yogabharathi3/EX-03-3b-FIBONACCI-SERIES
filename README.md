# EX-03-3b-FIBONACCI-SERIES
## AIM 
To write a C program to generate the Fibonacci series for the value 6. 
## ALGORITHM 
1. Start the program. 
2. Read number of terms to display. 
3. Add the previous two terms and store it in new term. 
4. Assign 2nd term to 1st term and 3rd term to 2nd term. 
5. Repeat steps 3 and 4 n number of times. 
6. Display the result. 
7. Stop the program. 
## PROGRAM 
```
#include<stdio.h> 
int main() 
{ 
 int n,f,f1=-1,f2=1; 
 scanf("%d",&n); 
 do 
 { 
 f=f1+f2; 
 f1=f2; 
 f2=f; 
 printf("%d ",f); 
 n--; 
 } 
 while(n>0); 
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/EX-03-3b-FIBONACCI-SERIES/assets/118899387/415a6d65-a5e6-4685-81bf-3ec7f81fc308)
## RESULT
Thus the program to generate the Fibonacci series for the value 6 has been executed successfully. 
