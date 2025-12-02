# EX 33 C program to read a file name from user and create that file using fopen().
## DATE:
## AIM:
To write a C program to read a file name from user and create that file using fopen().

## Algorithm
Start.

Define a variables.

Write a program to read a file name from user and create that file using fopen().

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End.

## Program:
```
#include <stdio.h>

int main()
{
    char filename[100];
    FILE *fp;

    scanf("%s", filename);

    fp = fopen(filename, "w");
    if (fp != NULL)
        printf("%s File Created Successfully\n", filename);

    printf("%s File Opened\n", filename);

    fclose(fp);
    printf("%s File Closed", filename);

    return 0;
}

```

## Output:

<img width="1004" height="324" alt="image" src="https://github.com/user-attachments/assets/fccd4aa0-ab1d-4ba7-b2de-0cf51dc8dd3c" />



## Result:

Thus the program was executed and the output was verified successfully.
