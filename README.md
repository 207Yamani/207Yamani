#include <stdio.h>
int main(){
int n=4;
int m=20;
if(n>m)
n=n+m-(m=n);
int x=0;
int y;
for(int i=0;i<n;i++){
if(i%n==0)
x=x+i;
else
y=y+i;
}
int diff=y-x;
printf("%d ",diff);
}
