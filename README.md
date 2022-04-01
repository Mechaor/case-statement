#include <stdio.h>
#include <stdlib.h>

int main()
{
    int mean;
    printf("Enter the mean");
    scanf("%i", &mean);

    switch(mean)


    {
    case 1:
        printf("Science");
        break;
    case 2:
        printf("Business");
        break;
    case 3:
        printf("Humanities");
        break;
    case 4:
        printf("Social Science");
        break;
    default:
        printf("Sorry, wrong input");
        break;
    }
    return 0;
}
