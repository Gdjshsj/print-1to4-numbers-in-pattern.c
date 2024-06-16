 #include<stdio.h>
int main()
{
    int n;
    printf("enter n value");
    scanf("%d",&n);
    for(int i=0;i<n;i++)          //row
    {
        for(int j=0;j<n-i;j++)      
        {
        printf("%d",i+1);
    }
    printf("\n");
    }
} 

