<!--Comment-->
<p> //write a programme that print floidtryangle.</p>

```c
#include<stdio.h>
int main()
{
    while(1)
    {
        int num,row,col,space,count=0;
        printf("Enter the number : ");
        scanf("%d",&num);
        for(row=1; row<=num; row++)
        {
            for(space=1; space<=50; space++) // for space is not mendatory
            {
                printf(" ");
            }
            for(col=1; col<=row; col++)
            {
                count++;
                printf("%d",count);
            }
            printf("\n");
        }
    }
}

```
_p_~~a~~tt__e__`rn`
<image src="./image/im.png" width="500" title="image"/>

go on . . .