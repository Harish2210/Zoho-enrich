#include<stdio.h>
int main()
{
int n,r,t,i=0,j,k=0,a[100];
scanf("%d\n%d",&n,&r);
t=n;
while(t>0){
    a[i++]=t%10;
    t=t/10;
}
for(j=i-1;j>=0,k<i;j--,k++){
    printf("%d",a[(j+r)%i]);
}
}
