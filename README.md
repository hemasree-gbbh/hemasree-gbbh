#include <stdio.h>
int main()
{
    int i, n,prod;
    printf("enter a number");
    scanf("%d",&n);
    for(i=1;i<=10;i++)

{
    prod=i*n;
    printf("%d*%d=%d\n",i,n,prod);
}
}
