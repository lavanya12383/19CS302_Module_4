# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE:17/03/2026
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
Start.
Define a variables a,b,c,min.
Write program to find minimum numbers.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End.   

## Program:
```
/*
C program to find minimum between three fraction numbers using conditional operator.
#include <stdio.h>
int main() {
float a, b, c, min;
scanf("%f%f%f", &a, &b, &c);
// Finding minimum using conditional operator 
min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);
printf("Minimum between %.3f, %.3f and %.3f = %.3f\n",a,b,c, min);
return 0;
}
Developed by: ARIGALA LAVANYA
RegisterNumber:  212222060019
*/
```

## Output:

<img width="1151" height="220" alt="image" src="https://github.com/user-attachments/assets/d6e694d9-cca5-473e-bdc1-1bc236b36b23" />


## Result:
Thus the program was executed and the output was verified successfully.
