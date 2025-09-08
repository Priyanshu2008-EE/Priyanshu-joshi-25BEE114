#include <stdio.h>

int main() {
    int hours;
    int minutes;

       printf("Enter hours: ");
    scanf("%d", &hours);

       minutes = hours * 60;

    printf("%d hour(s) is equal to %d minute(s).\n", hours, minutes);

    return 0;
}



