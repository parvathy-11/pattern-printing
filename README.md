# pattern-printing
#include<stdio.h>
int main()
{
    int n,a,i,j;
    scanf("%d",&n);
    for(i=1;i<=2*n-1;i++)
    {
        a=n;
        for(j=1;j<=2*n-1;j++)
        {
            printf("%d\t",a);
            if(i>j)
            a--;
            if(j>=(2*n)-i)
            a++;
        }
        printf("\n");
    }
}
