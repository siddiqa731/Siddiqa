# Siddiqa
AA&amp;SI Assignment
#include <stdio.h>
int main() {
    double a, c, product;
    printf("Enter two numbers: ");
    scanf("%lf %lf", &a, &c);  
 
    // Calculating product
    product = a * c;

    // %.2lf displays number up to 2 decimal point
    printf("Product = %.2lf", product);
    
    return 0;
}
