#include <stdio.h>

int main() {
    int minutes, hours, remaining_minutes;

       printf("Enter minutes: ");
    scanf("%d", &minutes);

        hours = minutes / 60;
    remaining_minutes = minutes % 60;

    
    printf("%d minute(s) is equal to %d hour(s) and %d minute(s).\n", minutes, hours, remaining_minutes);

    return 0;
}