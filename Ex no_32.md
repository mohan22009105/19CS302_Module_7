# EX 32 C program to display Hardware details such as price, product name and price using structure.
## DATE:
## AIM:
To write a C program to display Hardware details such as price, product name and price using structure.

## Algorithm

Start.

Define a variables.

Write a program to display hardware details such as price, product name and price using structure.

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End.

## Program:
```
#include <stdio.h>

struct hardware
{
    char code[50];
    char product[50];
    int price;
};

int main()
{
    struct hardware h[3];
    int i;

    for (i = 0; i < 3; i++)
        scanf("%s %s %d", h[i].code, h[i].product, &h[i].price);

    for (i = 0; i < 3; i++)
    {
        printf("QRcode:%s\n", h[i].code);
        printf("product:%s\n", h[i].product);
        printf("price :%d\n", h[i].price);
    }

    return 0;
}
```

## Output:

<img width="1013" height="492" alt="image" src="https://github.com/user-attachments/assets/8318fa3c-7858-4b19-bb81-173c788d99be" />



## Result:
Thus the program was executed and the output was verified successfully.
