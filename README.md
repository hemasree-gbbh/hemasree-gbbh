#include <stdio.h>
int n,i,temp,rev;
int main()
{
    printf("enter a number");
    scanf("%d",&n);
    for(i=0;n>0;i++)
    {
        rev=n%10;
        
       n= n/10;
       temp=temp*10+rev;
    }
    printf(" reversed digits are %d",temp);
}
