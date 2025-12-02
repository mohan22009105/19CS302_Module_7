# EX 31 C program to find the smallest among three numbers using Structure.

## AIM:
To write a C program to find the smallest among three numbers using Structure.

## Algorithm

Start.

Define a variables a,b,c.

Write program to find the smallest among the three numbers.

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End   

## Program:
```
#include <stdio.h>

struct nums
{
    int a, b, c;
};

int main()
{
    struct nums n;
    scanf("%d %d %d", &n.a, &n.b, &n.c);

    int smallest = n.a;

    if (n.b < smallest)
        smallest = n.b;
    if (n.c < smallest)
        smallest = n.c;

    printf("%d is the smallest number.", smallest);

    return 0;
}
```

## Output:

<img width="1037" height="225" alt="image" src="https://github.com/user-attachments/assets/54b5f538-c677-47b2-bb35-701139015e34" />




## Result:
Thus the program was executed and the output was verified successfully.
