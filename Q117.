//Write a program to take two sorted arrays of size m and n as input. Merge both the arrays such that the merged array is also sorted. Print the merged array.

#include <stdio.h>

int main() {
    int m, n, i, j, k;

    printf("Enter size of first array: ");
    scanf("%d", &m);

    int a[m];
    printf("Enter first sorted array:\n");
    for(i = 0; i < m; i++) {
        scanf("%d", &a[i]);
    }

    printf("Enter size of second array: ");
    scanf("%d", &n);

    int b[n];
    printf("Enter second sorted array:\n");
    for(i = 0; i < n; i++) {
        scanf("%d", &b[i]);
    }

    int merged[m + n];
    i = j = k = 0;

    // Merge using two pointers
    while(i < m && j < n) {
        if(a[i] < b[j]) {
            merged[k] = a[i];
            i++;
        } else {
            merged[k] = b[j];
            j++;
        }
        k++;
    }

    // Copy remaining elements
    while(i < m) {
        merged[k] = a[i];
        i++;
        k++;
    }

    while(j < n) {
        merged[k] = b[j];
        j++;
        k++;
    }

    printf("Merged array:\n");
    for(i = 0; i < m + n; i++) {
        printf("%d ", merged[i]);
    }

    return 0;
}
