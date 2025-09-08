#include <stdio.h>

int main() {
    float rupees, dollars;
    float conversionRate = 48.0;  // 1 Dollar = 48 Rupees

    printf("Enter amount in rupees: ");
    scanf("%f", &rupees);

    
    dollars = rupees / conversionRate;

    
    printf("%.2f Rupee(s) = %.2f Dollar(s)\n", rupees, dollars);

    return 0;
}