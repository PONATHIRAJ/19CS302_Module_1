# EX 1 C program to initialize the value as 5.8 & display the same.
## DATE:
## AIM:
To write a program to initialize the value as 5.8 & display the same.

## Algorithm
1. Start. 
2. Declare the variables. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Calculate the number of years using the formula: 
6. End . 

## Program:
```
#include <stdio.h> 
#include <math.h> 
int main() 
{ 
float p,n,r,si,ci; 
scanf("%f%f%f", &p,&n,&r); 
si=((p*n*r)/100); 
ci=(p)*(pow((1+ r/100),n)); 
printf("Simple Interest = %0.2f\nCompound Interest = %0.2f", si,ci); 
return 0; 
}
```

## Output:

![image](https://github.com/user-attachments/assets/619f0617-0be5-4028-a50b-412910d9b4ac)


## Result:
Thus the program was executed and the output was verified successfully.
