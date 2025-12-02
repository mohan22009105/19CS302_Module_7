# EX 35 C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## AIM:
To write a C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## Algorithm
Start.

Define a variables.

Write a program to read a file name from user and create that file and insert student roll numbers in to that file.

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End.
## Program:
```
#include <stdio.h>

int main()
{
    FILE *fp;

    fp = fopen("Hospital.txt", "w");
    printf("Hospital.txt File Created Successfully\n");
    printf("Hospital.txt File Opened\n");

    fclose(fp);
    printf("Hospital.txt File Closed");

    return 0;
}

```

## Output:

<img width="816" height="153" alt="image" src="https://github.com/user-attachments/assets/cbf408b2-b957-4984-9023-a3e4aac4c036" />




## Result:
Thus the program was executed and the output was verified successfully.
