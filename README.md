# hello-world
just another repository
#include <stdio.h>
int main()
{
    int i,j,n;
    for(i=1;i<=9;i++) {
        for(j=1;j<=i;j++) {
            printf("%d*%d=%d",j,i,i*j);}
        printf("\n");}
    return 0;
}
