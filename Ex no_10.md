# EX 10 C program for finding the factorial of a given number using function without return type with arguments.
## DATE:
## AIM:
To write a C program for finding the factorial of a given number using function without return type with arguments.

## Algorithm

1.Start the program and declare required variables (number and result).

2.Read the input number from the user.

3.Call a function (e.g., factorial(n)) and pass the number as an argument.

4.Inside the function, initialize a variable (fact = 1) and use a loop to multiply numbers from 1 to   n to calculate the factorial.

5.Display the factorial result inside the function and end the program.  

## Program:
```
#include<stdio.h>
int main()
{
    int a,s=1;
    scanf("%d",&a);
    for(int i=1;i<=a;i++)
    {
        s=s*i;
    }
    printf("Factorial value is: %d",s);
}
```

## Output:

<img width="709" height="159" alt="Screenshot 2026-03-19 130528" src="https://github.com/user-attachments/assets/a8ef931c-65c4-4d7e-8a67-aa03591b51a3" />


## Result:
Thus the program was executed and the output was verified successfully.
