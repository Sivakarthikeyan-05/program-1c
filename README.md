# program-1c
## c module 1 c
### EX 1)c) Finding whether a given character is alphabet or not.
**Date:** 24/1/2026
**NAME:** sivakarthikeyan .v
**ref no:** 25017090
### AIM:Write a C program to find whether the given character is alphabet or not.
### ALGORITHM:
1)Get input from the user. 
2)Find whether the input is alphabet or not using isalpha() function. 
3)Use if else statement to print the result.
###PROGRAM 

```
#include <stdio.h>
#include <ctype.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    if(isalpha(ch))
    printf("It is ALPHABET");
    else
    printf("It is NOT ALPHABET");
}
```
### OUTPUT

<img width="671" height="403" alt="image" src="https://github.com/user-attachments/assets/28625146-0029-4f58-b190-30abe00ff16b" />
### RESULT 
the output is executed successfully 
