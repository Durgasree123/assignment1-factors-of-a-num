#include <stdio.h>
void main()
{
int n,i;
printf("enter any number");
scanf("%d",&n);
for(i=1;i<=n;i++)
{
if(n%i==0)
{
printf("factors are %d\n",i);
}
}
getch();
}
