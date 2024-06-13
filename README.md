# Siddiqa
AA&amp;SI Assignment
#include <stdio.h>
int main() {
    double b, c, product;
    printf("Enter two numbers: ");
    scanf("%lf %lf", &b, &c);  
 
    // Calculating product
    product = b * c;

    // %.2lf displays number up to 2 decimal point
    printf("Product = %.2lf", product);
    
    return 0;
}
