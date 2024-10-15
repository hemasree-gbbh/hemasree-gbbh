#include <stdio.h>

int main() {
    int n,i,rev,temp;
    printf("Enter a number");
    scanf("%d",&n);
    for(i=1;n>0;i++)
    {
    rev=n%10;
    n=n/10;
    temp=temp*10+rev;
}
printf("Reversed digits are %d",temp);
}
