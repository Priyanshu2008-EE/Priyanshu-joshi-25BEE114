#include <stdio.h>

int main() {
    float kilograms, grams;

    // Ask user for input in kilograms
    printf("Enter weight in kilograms: ");
    scanf("%f", &kilograms);

    // Convert kilograms to grams
    grams = kilograms * 1000.0;

    // Display result
    printf("%.2f kilogram(s) = %.2f gram(s)\n", kilograms, grams);

    return 0;
}