# EX 17 C Program to compare two strings without using strcmp().
## DATE:17/03/2026
## AIM:
To write a C Program to compare two strings without using strcmp().

## Algorithm
Start.
Define a variables.
Write program to compare two strings using nested for loop and if statement.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End.

## Program:
```
/*
 C Program to compare two strings without using strcmp().
#include <stdio.h>
int main() {
 char str1[100], str2[100];
 int i = 0, flag = 0;
 scanf("%s", str1);
 scanf("%s", str2);
 while (str1[i] != '\0' || str2[i] != '\0') {
 if (str1[i] != str2[i]) {
 flag = 1;
 break;
 }
 i++; } 
if (flag == 0) 
printf("Strings are equal.\n");
else
 printf("Strings are not equal.\n");
 return 0;
}
Developed by: ARIGALA LAVANYA
RegisterNumber:  212222060019
*/
```

## Output:

<img width="974" height="225" alt="image" src="https://github.com/user-attachments/assets/f09ee039-14e0-4404-87b4-c68958195643" />


## Result:
Thus the program was executed and the output was verified successfully.
