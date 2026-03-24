# EX 8 C program for Multiplication and Division of two numbers using functions (Without argument and with return type)
## DATE:
## AIM:
To write a C program for Multiplication and Division of two numbers using functions (Without argument and with return type)

## Algorithm

1.Start the program and declare function prototypes multiply() and divide().

2.In the main() function, call the multiply() function to get the multiplication result and store it in a variable.

3.Display the multiplication result using printf.

4.Call the divide() function, which reads two numbers, performs division, and returns the result.

5.Print the division result and end the program.

## Program:
```
#include<stdio.h>
int multiply();
int divide();
int main()
{
    int r,s;
    r=multiply();
    printf("Multiplication: %d\n",r);
    s=divide();
    printf("Division: %d",s);
    
}
int multiply()
{
    int a,b,c;
    scanf("%d%d",&a,&b);
    c=a*b;
    return c;
}
int divide()
{
    int d,e,f;
    scanf("%d%d",&d,&e);
    f=d/e;
    return f;
}

    
```

## Output:

<img width="603" height="236" alt="Screenshot 2026-03-19 131615" src="https://github.com/user-attachments/assets/e9096a9f-dba5-413e-adbc-50c976fee1a9" />


## Result:
Thus the program was executed and the output was verified successfully.
