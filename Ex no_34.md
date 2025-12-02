# EX 34 C program to read a file name from user and create that file and insert student roll numbers in to that file.

## AIM:
To write a C program to read a file name from user and create that file and insert student roll numbers in to that file.

## Algorithm
. Start.

Define a variables.

Write a program to read a file name from user and create that file and insert student roll numbers in to that file.

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End  

## Program:
```
#include <stdio.h>

int main()
{
    char filename[100];
    int n, i, roll;
    FILE *fp;

    scanf("%s", filename);

    fp = fopen(filename, "w");
    printf("%s Opened\n", filename);

    scanf("%d", &n);

    for (i = 0; i < n; i++)
    {
        scanf("%d", &roll);
        fprintf(fp, "%d\n", roll);
    }

    fclose(fp);
    printf("Data added Successfully");

    return 0;
}

```

## Output:

<img width="757" height="147" alt="image" src="https://github.com/user-attachments/assets/9167f43d-7574-4c8f-a05e-7825f0117240" />




## Result:
Thus the program was executed and the output was verified successfully.
