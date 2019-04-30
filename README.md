# C-pyramid-shapes
learning how to program in C


#include<stdio.h>

int main(void)
{

int rows,i,j,sp;
printf("enter the num of rows: ");
scanf("%d", &rows);
printf("printing the pattern\n");

    for(i=1;i<=rows;i++)
    {

        for(sp=1;sp<=rows-i;sp++)

        {
           printf(" ");
        }

        for(j=1;j<=i;j++)

        {
            printf("*");
            printf(" ");
        }


    printf("\n");
    }

    for(i=1;i<=rows;i++)
        {
            for(sp=1;sp<=i;sp++)
            {
                printf(" ");
            }

            for(j=1;j<=rows-i;j++)
            {
                printf("*");
                printf(" ");

            }
        printf("\n");

        }

    for(i=1;i<=rows;i++)
    {
        printf("%i\n",i);
    }

}
