## print all the letters of the English alphabet.

SAMPLE OUTPUT : CAPS and add space to each alphabet

A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
# AIM:
To write a C program to print all the letters of the English alphabet.

# Algorithm
1. Start
2. Initialize a character variable ch with 'A'.
3. Loop from 'A' to 'Z':
4. Print the character.
5. Print a space after each character.
6. End the loop once 'Z' is printed.
7. End
# Program:
#include <stdio.h>

int main() {
    char ch;
    
    for (ch = 'A'; ch <= 'Z'; ch++) {
        printf("%c ", ch);
    }
    
    return 0;
}
# Output:

<img width="567" height="153" alt="image" src="https://github.com/user-attachments/assets/43297fbd-2be8-4ad6-8a83-cad7b99ce566" />

# Result:

Thus the program was executed and the output was verified successfully.
