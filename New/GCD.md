# GCD

#include<stdio.h>

int main() {

 int m,n,r=1;

 printf("\n Enter value for m,n\n");

 scanf("%d%d",&m,&n);

 while(r!=0)

{

 r=n%m;

 n=m;

 m=r;

}

 printf("\n GCD=%d \n",n);

 return 0;
}

## Output

Enter value for m,n

12 14

GCD=2
