# Module-4 Day-4 SEB
## AIM:
To write a C program to input a number from the user and check whether the number is positive, negative or zero using a switch case. 

## For example:

## Program:
```c
#include<stdio.h>
int main(){
    int n;
    scanf("%d",&n);
    switch(n>0){
        case 1:
        printf("Number is positive.");
        break;
        case 0:
        switch(n<0){
            case 1:
            printf("Number is negative.");
            break;
            case 0:
            printf("Number is zero.");
            break;
        }
        break;
    }
    return 0;
}
```
## Result:
