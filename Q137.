//Create an enum for user roles (ADMIN, USER, GUEST) and display messages based on role.


#include <stdio.h>

int main() {
    // Enum for user roles
    enum Role {ADMIN, USER, GUEST};

    enum Role r;

    // Ask user for role
    printf("Enter role (0 for ADMIN, 1 for USER, 2 for GUEST): ");
    scanf("%d", &r);

    // Display message based on role
    switch(r) {
        case ADMIN:
            printf("Welcome, Admin! You have full access.\n");
            break;
        case USER:
            printf("Welcome, User! You have limited access.\n");
            break;
        case GUEST:
            printf("Welcome, Guest! You have guest access.\n");
            break;
        default:
            printf("Invalid role.\n");
    }

    return 0;
}
