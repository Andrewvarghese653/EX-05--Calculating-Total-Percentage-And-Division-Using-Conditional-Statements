# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
```
#include <stdio.h>
int main()  
{
    int n;
    scanf("%d",&n);
    if(n>=70 && n<=100)
    {
        printf("...FIRST CLASS WITH DISTINCTION...");
    }
    else if(n>=60 && n<70)
    {
        printf("...FIRST CLASS...");
    }
    else if(n>=50 && n<60)
    {
        printf("...SECOND CLASS...");
    }
    else if(n>=40 && n<50)
    {
        printf("...THIRD CLASS...");
    }
    else
    {
        printf("...U r Failed...Better luck next time");
    }
    return 0;
}
```

## OUTPUT:
![Screenshot 2025-04-27 091651](https://github.com/user-attachments/assets/70562b39-e69a-4526-8ea3-3c96d4ce73f8)
## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

