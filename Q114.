//Write a program to take a string s as input. The task is to find the length of the longest substring without repeating characters. Print the length as output.

#include <stdio.h>
#include <string.h>

int main() {
    char s[100];
    int i, j, k;

    printf("Enter string: ");
    scanf("%s", s);

    int n = strlen(s);
    int maxLen = 0;

    // Check all substrings
    for(i = 0; i < n; i++) {
        int count[256] = {0};   // to check repeating chars
        int currLen = 0;

        for(j = i; j < n; j++) {
            if(count[(unsigned char)s[j]] == 1) {
                break;  // repeated character found
            }
            count[(unsigned char)s[j]] = 1;
            currLen++;

            if(currLen > maxLen) {
                maxLen = currLen;
            }
        }
    }

    printf("Length of longest substring = %d\n", maxLen);

    return 0;
}
