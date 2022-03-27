#include<stdio.h>
void main()
{
    int x,n,sum;
    printf("Enter Number of natural no to be dispalayed\n");
    scanf("%d",&n);
    printf("N natural numbers in reversed order are:\n");
    for(x=1;x<=n;x++)
    {
        printf("%d\n",x);
        sum=n*(n+1)/2;
    }
    printf("Sum is:\t%d",sum);
}
