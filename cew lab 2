// Exercise lab 01

#include <stdio.h>
#include <stdlib.h>

int main()
{
     int n;
    printf("Enter the value of n: ");
    scanf("%d", &n);

    int sum = 0;

    for (int a = 1; a <= 20; a++) {
        if (a % 2 != 0) {
            printf("Odd Number: %d\n", a);
            sum += a;
        }
    }
    printf("Sum of the first %d odd natural numbers: %d\n", n, sum);
    return 0;
}


//  Exercise lab 02
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int n,i, spaces;
    printf("Enter the number of rows: ");
    scanf("%d", &n);
    spaces = n-1;

    for (int i = 1; i <= n; i++) {
       for (int j=spaces; j>=1; j--){
            printf(" ");

       }
       for (int k =0; k<i; k++){
            printf("* ");
       }

       printf("\n");
       spaces--;
    }
    return 0;
}


// Exercise 03
#include <stdio.h>
#include <stdlib.h>

int main()
{
    char str1[] = "Anoosha";
    char str2[] = "Anoosha";
    int equal = 1;

    for (int i = 0; str1[i] != '\0' || str2[i] != '\0'; i++) {
        if (str1[i] != str2[i]) {
            equal = 0;
            break;
        }
    }

    if (equal) {
        printf("The strings are equal.\n");
    } else {
        printf("The strings are not equal.\n");
    }

    return 0;
}


// Exercise 04
#include <stdio.h>
#include <stdlib.h>

int main()
{
     char inputString[100];

    printf("Enter a string: ");
    scanf("%s", inputString);

    for (int i = 0; inputString[i] != '\0'; i++) {
        if (inputString[i] >= 'a' && inputString[i] <= 'z') {
            inputString[i] = inputString[i] - 'a' + 'A';
        } else if (inputString[i] >= 'A' && inputString[i] <= 'Z') {
            inputString[i] = inputString[i] - 'A' + 'a';
        }
    }

    printf("Final string: %s\n", inputString);

    return 0;
}


// Exercise 05
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int arr[] = {1, 2, 2, 3, 4, 4, 5, 6, 6, 7};
    int n = sizeof(arr) / sizeof(arr[0]);

    printf("Unique elements in the array: ");

    for (int i = 0; i < n; i++) {
        int count = 0;

        for (int j = 0; j < n; j++) {
            if (i != j && arr[i] == arr[j]) {
                count++;
                break;
        }

        if (count == 0) {
            printf("%d ", arr[i]);
        }
    }

    printf("\n");
    return 0;
}


// Exercise 06
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int feet1, inches1, feet2, inches2;

    printf("Enter the first distance (feet inches): ");
    scanf("%d %d", &feet1, &inches1);

    printf("Enter the second distance (feet inches): ");
    scanf("%d %d", &feet2, &inches2);

    int totalFeet = feet1 + feet2;
    int totalInches = inches1 + inches2;

    if (totalInches >= 12) {
        totalInches -= 12;
        totalFeet++;
    }
    printf("Sum of distances: %d feet %d inches\n", totalFeet, totalInches);
    return 0;
}


