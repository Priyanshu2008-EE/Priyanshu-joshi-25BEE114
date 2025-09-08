#include <stdio.h>

int main() {
    float dollars, rupees;
    float conversionRate = 48.0;  // 1 Dollar = 48 Rupees

       printf("Enter amount in dollars: ");
    scanf("%f", &dollars);

        rupees = dollars * conversionRate;

     printf("%.2f Dollar(s) = %.2f Rupee(s)\n", dollars, rupees);

    return 0;

}
