//Write a program to take a string input. Change it to sentence case.

#include <stdio.h>
#include <ctype.h>

int main() {
    char s[200];
    int i;

    printf("Enter a string: ");
    fgets(s, sizeof(s), stdin);

    // Convert entire string to lowercase first
    for(i = 0; s[i] != '\0'; i++) {
        s[i] = tolower(s[i]);
    }

    // Capitalize first alphabetic character
    for(i = 0; s[i] != '\0'; i++) {
        if(s[i] >= 'a' && s[i] <= 'z') {
            s[i] = s[i] - 32;   // uppercase
            break;
        }
    }

    printf("Sentence case: %s", s);

    return 0;
}
