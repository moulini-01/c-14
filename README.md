//# c-14
//even series with in range
#include <stdio.h>
int main()
{
    int start,end,sum=0;
    printf("enter the starting number:");
    scanf("%d",&start);
    printf("enter the ending number:");
    scanf("%d",&end);
    for(int i=start;i<=end;i++)
    {
        if(i%2==0)
        {
            sum+=i;
        }
    }
    printf("even series within range :%d",sum);
    return 0;
}
