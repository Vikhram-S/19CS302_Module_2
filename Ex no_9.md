# EX 9 C program to find the sum of digits using while loop without using modulus operator
## DATE:
## AIM:
To write a C program to find the sum of digits using while loop without using modulus operator

## Algorithm

1.Start the program and declare variables c, sum, t, and a character array n.

2.Read the input number as a string using scanf to avoid using the modulus operator.

3.Initialize sum = 0 and c = 0.

4.Use a while loop to traverse each digit until the null character ('\0') is reached; convert each character to an integer using t = n[c] - '0' and add it to sum.

5.Display the sum of digits and stop the program.

## Program:
```
#include <stdio.h>  
int main()  
{  
   int c, sum, t;  
   char n[1000];  
   scanf("%s", n);  
   sum = c = 0;  
   while (n[c] != '\0') {  
      t   = n[c] - '0';   
      sum = sum + t;  
      c++;  
   }  
   printf("%d",sum);  
   return 0;  
}  
```

## Output:

<img width="581" height="200" alt="Screenshot 2026-03-19 131230" src="https://github.com/user-attachments/assets/550b287b-57de-4dae-b379-4d7f1a7ca224" />


## Result:
Thus the program was executed and the output was verified successfully.
