# Lokesh#
#include <stdio.h>
#include <math.h>

int main() {
    float principal, rate, time, amount, compound;

    // Input the principal amount
    printf("Enter the principal amount: ");
    scanf("%f", &principal);

    // Input the rate of interest
    printf("Enter the rate of interest (in percentage): ");
    scanf("%f", &rate);

    // Input the time in years
    printf("Enter the time (in years): ");
    scanf("%f", &time);

    // Calculate the compound interest
    amount = principal * pow((1 + rate / 100), time);
    compoundInterest = amount - principal;

    // Output the results
    printf("The compound interest is: %.2f\n", compoundInterest);
    printf("The amount after %.2f years is: %.2f\n", time, amount);

    return 0;
}
