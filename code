#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n; scanf("%d",&n);
    int a[n];
    for(int i=0;i<n;i++)scanf("%d",&a[i]);
    int max=0;
    for(int i=n-1;i>=0;i--)
    {
        int r=a[i];
        a[i]=max;
        if(r>max)max=r;
    }
    for(int i=0;i<n;i++)printf("%d ",a[i]);
    return 0;
}
