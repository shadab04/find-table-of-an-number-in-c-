# find-table-of-an-number-in-c-
#include<stdio.h>
void table(int n);
int main()
{
    int n;
    printf("enter the number:");
    scanf("\n%d",&n);
    table(n);
    return 0;
}
void table(int n)
{
    for(int i=1;i<=10;i++)
    {
        printf("\n %d",i*n);
    }
}
