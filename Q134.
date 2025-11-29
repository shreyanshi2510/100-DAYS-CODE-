//Define an enum with SUCCESS, FAILURE, and TIMEOUT, and print messages accordingly.

#include <stdio.h>

int main() {
    // Enum for status
    enum Status {SUCCESS, FAILURE, TIMEOUT};

    enum Status s;

    // Ask user for status value
    printf("Enter status (0 for SUCCESS, 1 for FAILURE, 2 for TIMEOUT): ");
    scanf("%d", &s);

    // Print message based on status
    switch(s) {
        case SUCCESS:
            printf("Operation completed successfully.\n");
            break;
        case FAILURE:
            printf("Operation failed.\n");
            break;
        case TIMEOUT:
            printf("Operation timed out.\n");
            break;
        default:
            printf("Invalid status.\n");
    }

    return 0;
}
