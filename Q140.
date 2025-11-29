//Define a struct with enum Gender and print person's gender.


#include <stdio.h>

// Enum for gender
enum Gender {MALE, FEMALE, OTHER};

// Struct for a person
struct Person {
    char name[50];
    int age;
    enum Gender gender;
};

int main() {
    struct Person p;

    // Input person details
    printf("Enter name: ");
    scanf("%s", p.name);

    printf("Enter age: ");
    scanf("%d", &p.age);

    printf("Enter gender (0 for MALE, 1 for FEMALE, 2 for OTHER): ");
    scanf("%d", (int*)&p.gender);  // cast to int pointer for enum input

    // Array of gender names for printing
    const char *genderNames[] = {"MALE", "FEMALE", "OTHER"};

    // Print person details
    printf("\n--- Person Details ---\n");
    printf("Name: %s\n", p.name);
    printf("Age: %d\n", p.age);
    printf("Gender: %s\n", genderNames[p.gender]);

    return 0;
}
