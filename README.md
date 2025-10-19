# Program-4-d
## C-Module 4
## EX_NO-04)d)-STRINGS
### Date: 19-10-2025
### Name: Anish D
### Register Number:25010086
## AIM:
Write a C program to count the total number of words in a given string using While loop.
## ALGORITHM:
1. Start the program.
2. Declare a character array to store the input string and an integer variable space initialized to 0.
3. Read a line of text from the user using scanf("%[^\n]", word).
4. Use a for loop to iterate through each character of the string:

     a. If the character is a space (' '), increment the space counter.

5. After the loop, print the total number of words by adding 1 to the space counter.
6. End the program.

## PROGRAM:
```
#include<stdio.h>
#include<string.h>
#include<ctype.h>
int main()
{
    char word[100];
    int space=0;
    scanf("%[^\n]",word);
    for(int i=0;i<strlen(word);i++)
    {
       if(word[i]==' ')
       space++;
    }
    printf("%d",space+1);
}
```
## OUTPUT:
<img width="852" height="232" alt="Screenshot 2025-10-19 225056" src="https://github.com/user-attachments/assets/2da98427-cb4b-49fd-b063-98751bcccd32" />

## RESULT:
Thus the program to count the total number of words in a given string using While loop has been executed successfully
