//Write a program to take an integer array arr and an integer k as inputs. The task is to find the first negative integer in each subarray of size k moving from left to right. If no negative exists in a window, print "0" for that window. Print the results separated by spaces as output.

#include <stdio.h>

int main() {
    int n, k, i, j;

    printf("Enter size of array: ");
    scanf("%d", &n);

    int arr[n];

    printf("Enter array elements:\n");
    for(i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }

    printf("Enter k: ");
    scanf("%d", &k);

    if(k > n) {
        printf("Invalid input\n");
        return 0;
    }

    printf("Maximums of each window:\n");
    for(i = 0; i <= n - k; i++) {
        int max = arr[i];
        for(j = i; j < i + k; j++) {
            if(arr[j] > max) {
                max = arr[j];
            }
        }
        printf("%d ", max);
    }

    return 0;
}
