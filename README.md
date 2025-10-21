# EX-04 Check Voter Eligibility

## AIM:
To write a C program to read the age of a candidate and determine whether he/she is eligible to vote.

## ALGORITHM:
1. Start
2. Declare an integer variable age.
3. Prompt the user to enter their age.
4. Read the age using scanf.
5. If age >= 18, display “Eligible to vote”.
6. Else, display “Not eligible to vote”.
7. Stop

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int age;
    printf("Enter your age: ");
    scanf("%d",&age);
    if(age>=18)
    {
        printf("Eligible for casting your vote");
    }
    else
    {
        printf("Not Eligible to caste your vote");
    }
    return 0;
} 
```

## OUTPUT:

<img width="669" height="122" alt="image" src="https://github.com/user-attachments/assets/b10b9801-006f-4bd8-9765-c1c39f290afe" />

## RESULT:
The program correctly determines whether a person is eligible for voting based on their age.
