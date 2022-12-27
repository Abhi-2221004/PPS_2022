
### Program 31: Write a program to get user input
```C
#include<stdio.h>

int main(){
    char usr[20];
    int roll;
    printf("Enter username -> ");
    scanf("%s",usr);
    printf("Enter Roll number -> ");
    scanf("%d",&roll);

    printf("\nUsername -> %s\n",usr);
    printf("Password -> %d\n",roll);

    return 0;
}
```
Output:
```C
Enter username -> Abhi Negi
Enter Roll number -> 2221004

Username -> Abhi Negi
Password -> 2221004
