# 19ecb132
#include<stdio.h>
int main()
{
    int num,factorial=1,i;
    scanf("%d",&num);
    if(num<0)
    {
        printf("negative number");
    }
        else if (num>=10)
    {
        printf("too big a number");
    }
    else
    {
        for(i=1;i<=num;i++)
        factorial=factorial*i;
        printf("%d",factorial);
    }
}
