# EX 7  C program to print the triangular  pattern using loop.
## DATE:
## AIM:
To write a  C program to print the  triangular  pattern using loop.

## Algorithm

1.Start the program and declare variables i, j, and column.

2.Read the number of rows (column) from the user using scanf.

3.Use an outer loop from i = column down to 1 to control the number of rows.

4.Use an inner loop from j = 1 to i to print # in each row.

5.Print a newline after each row to form the triangular pattern and end the program.

## Program:
```
#include<stdio.h>
int main()
{
    int i,j,column;
    scanf("%d",&column);
    for(i=column;i>=1;i--) 
    
    
    {
        for(j=1;j<=i;j++) 
        {
            printf("#");
        }
        printf("\n");
        
    }
    return 0;
}
```

## Output:

<img width="402" height="243" alt="Screenshot 2026-03-19 132120" src="https://github.com/user-attachments/assets/a13d6c48-1e06-424e-8a12-12381cd38392" />


## Result:
Thus the program was executed and the output was verified successfully.
