#include <stdio.h>

int main() {
    int n, i;
    float price, total = 0;

    printf("Enter number of items: ");
    scanf("%d", &n);

    for(i = 1; i <= n; i++) {
        printf("Enter price of item %d: ", i);
        scanf("%f", &price);
        total += price;
    }

    printf("Total Bill Amount = %.2f\n", total);
    return 0;
}
# shop
Enter number of items: 3
Enter price of item 1: 50
Enter price of item 2: 30.5
Enter price of item 3: 20
