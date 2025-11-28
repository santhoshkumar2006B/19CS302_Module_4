# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE:
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
1. Start. 
2. Define a variables a,b,c,min. 
3. Write program to find minimum numbers. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End.


## Program:
```
/*
C program to find minimum between three fraction numbers using conditional operator.
Developed by: santhosh kumar b
RegisterNumber:  212223060249
*/
#include <stdio.h> 
int main() { 
float a, b, c, min; 
scanf("%f%f%f", &a, &b, &c); 
// Finding minimum using conditional operator 
min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c); 
 
printf("Minimum between %.3f, %.3f and %.3f = %.3f\n",a,b,c, min); 
return 0; 
} 
```

## Output:
<img width="661" height="181" alt="image" src="https://github.com/user-attachments/assets/b7de5e3a-e12a-411a-94c0-5666777eaed7" />




## Result:
Thus the program was executed and the output was verified successfully.
