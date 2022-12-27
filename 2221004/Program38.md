### Program 38:Write a program to use conditional operator
```C
#include <stdio.h>

int main(){
    int x;
    printf("Enter a number: ");
    scanf("%d", &x);
    (x%2==0)?printf("Number is even\n"):printf("Number is odd\n");

    return 0;
}
```
### Output:
```C
Enter a number: 3124
Number is even
