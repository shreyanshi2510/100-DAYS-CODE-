//Write a program to take an integer array as input. Only one element will be repeated. Print the repeated element. Try to find the result in one single iteration.

#include <stdio.h>

int main() {
    int n, i, x;

    printf("Enter size of array: ");
    scanf("%d", &n);

    int arr[n];
    int freq[1000] = {0};   // assuming array values are within 0–999

    printf("Enter array elements:\n");
    for(i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }

    // One pass to find the repeated element
    for(i = 0; i < n; i++) {
        x = arr[i];
        freq[x]++;

        if(freq[x] == 2) {   // repeated found
            printf("Repeated element = %d\n", x);
            return 0;
        }
    }

    printf("No repeated element\n");
    return 0;
}
