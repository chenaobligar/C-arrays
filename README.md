
#include <stdio.h>
int  main()

{
    int a[100],s,i,n;
    
    printf(" Size of element:");
    scanf("%d", &n);
    
    
    for(i=0;i<n;i++)
{
    printf("Elements:");
    scanf("%d", &a[i]);
}
    printf("Sum of all array elements:");
    for(i=0;i<n;i++)
{
    s=s+a[i];
}
printf(" %d ",s);
}
