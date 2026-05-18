#include <stdio.h>
#include <string.h>

int main() {
    char str[100];
    int i;

    // Taking input from user
    printf("Enter a string: ");
    scanf("%s", str);

    // XOR each character with 0
    for(i = 0; str[i] != '\0'; i++) {
        str[i] = str[i] ^ 0;
    }

    // Display result
    printf("Result after XOR with 0: %s\n", str);

    return 0;
}
