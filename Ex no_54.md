## print all the letters of the English alphabet.

SAMPLE OUTPUT : CAPS and add space to each alphabet

A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
Algorithm:
Start
Initialize a character variable ch with 'A'.
Loop from 'A' to 'Z':
Print the character.
Print a space after each character.
End the loop once 'Z' is printed.
End
Program:
~~~c
#include <stdio.h>

int main() {
    char ch;
    
    for (ch = 'A'; ch <= 'Z'; ch++) {
        printf("%c ", ch);
    }
    
    return 0;
}
~~~c
Output:

![image](https://github.com/user-attachments/assets/c57cdf27-90e7-4a09-918b-fd8a4eebd71b)

Result:
Thus the program was executed and the output was verified successfully.
