#include <stdio.h>

int main() {
    float dollars, rupees;
    float conversionRate = 48.0;  // 1 Dollar = 48 Rupees

    // Ask user for amount in dollars
    printf("Enter amount in dollars: ");
    scanf("%f", &dollars);

    // Convert to rupees
    rupees = dollars * conversionRate;

    // Display result
    printf("%.2f Dollar(s) = %.2f Rupee(s)\n", dollars, rupees);

    return 0;
}