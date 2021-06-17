# Square-hollow-pattern
#include<stdio.h>
int main()
{  int row,star,space,n; 
   printf("Enter no of rows:");
   scanf("%d",&n);
   for(row=1;row<=n;row++)
   {
       if(row==1||row==n)
       {
           for(star=1;star<=n;star++)
           printf("*");
           printf("\n");
        }  
        else
        {
            printf("*");
            for(space=1;space<=n-2;space++)
            printf(" ");
            printf("*");
            printf("\n");
        }
        
   }
    return 0;
}
        
