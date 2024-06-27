#include <stdio.h>
int main()
{
    int arr[5],sum=0;
   for(int i=0;i<5;i=i+2)
   scanf("%d",&arr[i]);
   
   for(int i=0;i<5;i++)
   printf("%d\t",arr[i]);
   printf("\n");
   
   for(int i=0;i<5;i++)
    sum=sum+arr[i];
    printf("%d",sum);
}
