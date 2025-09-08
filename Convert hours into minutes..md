#include <stdio.h>

int main() {
    int hours;
    int minutes;

    // Ask user for input
    printf("Enter hours: ");
    scanf("%d", &hours);

    // Convert to minutes
    minutes = hours * 60;

    // Display result
    printf("%d hour(s) is equal to %d minute(s).\n", hours, minutes);

    return 0;
}


