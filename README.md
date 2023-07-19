#include<stdio.h>
int main(){
    int f[50],n,i;

    printf("Enter the fibonnaci number: ");
    scanf("%d",&n);

    f[0]=0;
    f[1]=1;

    for(i=2;i<n;i++){

        f[i]=f[i-1]+f[i-2];

    }
    printf("\n");
    for(i=0;i<n;i++){
        printf("%d ",f[i]);
    }
    return 0;
}
