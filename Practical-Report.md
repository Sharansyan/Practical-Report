   #        **PROGRAMMING FOR PROGRAM SOLVING**
   #             ESC-18105
##   NAME-*SHARANJIT SINGH*
##   ROLL NO-*1914103*
##   BRANCH-*CIVIL*
##   SECTION-*CE(B2)*
![LOGO](https://blog.coachingkaro.org/wp-content/uploads/2019/07/logo.jpg)
## **DEPARTMENT OF CIVIL ENGENEERING**
# **GURU NANAK DEV ENGENEERING COLLEGE,LUDHIANA**
---------------------------------------------------------------------------
1. Hello World

#include<stdio.h>
void main()
{
puts("\nHello World\n");
}
---------------------------------------------------------------------------
2. To Find Sum

#include<stdio.h>
int main()
{
        float x,y,z;

        printf("\nEnter The First Numder: ");
        scanf("%f", &x);

        printf("\nEnter The Second Numder: ");
        scanf("%f", &y);

        z = x+y;

        printf("\nAnswer is: = %.3f", z);

        return 0;
}
----------------------------------------------------------------------------
3. Table

#include<stdio.h>
int main()
{
        float x;
        int n;

        printf("\nEnter The Table: ");
        scanf("%f",&x);

        printf("\nEnter No. Times: ");
        scanf("%d",&n);

        for(int y=1; y<=n; y++)
  {
        printf("\n%.2f x %d = %.3f",x,y,x*y);
  }
        return 0;
}
-----------------------------------------------------------------------------
4. Circle

#include<stdio.h>
int main()
{
        float r,P,A,V;
        float pi = 22/7.0;

        printf("\nEnter The Radius of Circle: ");
        scanf("%f",&r);

        P = 2*pi*r;
        A = pi*r*r;
        V = 4*pi*r*r*r/3.0;

        printf("\nPerimeter of Circle is: = %.2f",P);

        printf("\nArea of Circle is: = %.2f",A);

        printf("\nVolume of Circle is: = %.2f",V);

        return 0;
}
---------------------------------------------------------------------------
5. Square

#include<stdio.h>
int main()
{
        float h,b,A,P;

        printf("\nEnter Height: ");
        scanf("%f",&h);

        printf("\nEnter Bredth: ");
        scanf("%f",&b);

        A = h*b;
        P = 2*(h+b);

        printf("\nArea of Sqare (or) Rectangle: = %.3f",A);
        printf("\nPerimeter of Sqare (or) Rectangle: = %.3f",P);

        return 0;
}
-------------------------------------------------------------------------
6. To find Interest

#include<stdio.h>
int main()
{
        float P,R,T,Interest;
{
        printf("\nEnter The Principal Amount: ");
        scanf("%f", &P);

        printf("\nEnter The Interest Rate: ");
        scanf("%f", &R);
        
        printf("\nEnter The Time (in months): ");
        scanf("%f", &T);

        Interest = P*T*R/100;
        
        printf("\nSimple Intesest is: = %.2f", Interest);

}
        return Interest;
}
----------------------------------------------------------------------
7. To Find Maximum

#include<stdio.h>
int max(float x,float y);
int main()
{
        float x,y,z;

        printf("\nEnter The First Value: ");
        scanf("%f",&x);

        printf("\nEnter The Second Value: ");
        scanf("%f",&y);

        z = max(x,y);

        printf("\nMaximum value is: %.2f\n", z);

        return 0;
}
int max(float x,float y)
{
        float result;

        if(x<y)
                result = y;
        else
                result = x;

        return result;
}
----------------------------------------------------------------------
8. Sum of Constants

#include<stdio.h>
int main()
{
        int a=100,b=120,c;
        c = a+b;
        printf("\na=100\nb=120\nSum  of a and b is :%d",c);
        return 0;
}
----------------------------------------------------------------------
9. To Find Minimum

#include<stdio.h>
int min(float x,float y);
int main()

{
float x,y,z;

        printf("\nEnter The First Value: ");
        scanf("%f",&x);

        printf("\nEnter The SecondValue: ");
        scanf("%f",&y);

        z = min(x,y);

        printf("\nMinimum value is: %.2f\n", z);

        return 0;
}

int min(float x,float y)

{
        float result;

        if(x<y)
                result = x;
        else
                result = y;

        return result;
}
----------------------------------------------------------------------
10. Bio Data of Students
  
#include<stdio.h>
int main()
{
        int n,R;
        char name[25];

        printf("\nEnter The Number of Students: ");
        scanf("%d",&n);

        for(int i=1; i<=n;i++)
{
        printf("\nEnter The Name of The Student : ");
        scanf("%s", name);

        printf("Enter The Roll No. of Students: ");
        scanf("%d",&R);

        printf("\nName = %s\nRoll No. = %d\n", name,R);
}
        return 0;
}
----------------------------------------------------------------------
11. Arithmetic Operators

#include<stdio.h>
int main()
{

        float x,y,a;

        printf("\nEnter The Value of x: ");
        scanf("%f",&x);

        printf("\nEnter The Value of y: ");
        scanf("%f",&y);

        a = x+y;
        printf("x + y = %.3f\n",a);
        a = x-y;
        printf("x - y = %.3f\n",a);
        a = y-x;
        printf("y - x = %.3f\n",a);
        a = x*y;
        printf("x * y = %.3f\n",a);
        a = x/y;
        printf("x/y = %.3f\n",a);
        a = y/x;
        printf("y/x = %.3f\n",a);

        return 0;
}
----------------------------------------------------------------------
12. Assignment Operators

#include<stdio.h>
int main()
{

        float x,a;

        printf("\nEnter The Value of x: ");
        scanf("%f",&x);

        a = x;
        printf("Answer is a = x %.3f\n",a);
        a +=x; //answer is a+x
        printf("Answer is a+x = %.3f\n",a);
        a -=x; //answer is a-x
        printf("Answer is a-x = %.3f\n",a);
        a *=x; //answer is a*x
        printf("Answer is a*x = %.3f\n",a);
        a /=x; //answer is a/x
        printf("Answer is a/x= %.3f\n",a);

        return 0;
}
----------------------------------------------------------------------
13. Operator Precedence

#include<stdio.h>
 
int main()
{
        float a,b,c,d,A;

        printf("\nEnter The Value of a: ");
        scanf("%f",&a);

        printf("Enter The Value of b: ");
        scanf("%f",&b);

        printf("Enter The Value of c: ");
        scanf("%f",&c);

        printf("Enter The Value of d: ");
        scanf("%f",&d);

        A = (a+b)*(c+d);
        printf("\n (a+b)*(c+d) = %.3f",A);
        A = (c+d)*a*b;
        printf("\n (c+d)*a*b = %.3f",A);
        A = a*d/(c-b-a);
        printf("\n a*d/(c-b-a) = %.3f",A);
        A = (b-c)*(a-d);
        printf(" (b-c)*(a-d) = %.3f",A);

        return 0;
}
----------------------------------------------------------------------
14. Average

#include<stdio.h>
float average();

int main()
{
  printf("\nAverage is: %.2f",average());
  return 0;
}

 float average()
{
 float x,y,z,s,a;

  printf("\nEnter The First Value: ");
  scanf("%f",&x);

  printf("Enter The Second Value: ");
  scanf("%f",&y);

  printf("Enter The Third Value: ");
  scanf("%f",&z);

  s = x+y+z;
  a = s/3;
  return a;
}
----------------------------------------------------------------------
15. F using #

#include<stdio.h>
int main()
{

        printf("\n########\n#\n#\n#\n#####\n#\n#\n#\n#\n#\n#\n");
        return 0;

}
----------------------------------------------------------------------
16. FizzBuzz

#include<stdio.h>
int main()
{
  int n;
  printf("\nEnter the Interger: ");
  scanf("%d",&n);

  if(n%3==0)
  printf("\nFizz");
  if(n%5==0)
  printf("Buzz\n");
  else
  printf("\n%d",n);
  return 0;
}
----------------------------------------------------------------------
17. Print Calculator

#include<stdio.h>
void main()
{
puts("\n\
 _______________\n\
| 1 | 2 | 3 |   |\n\
|___|___|___|   |\n\
| 4 | 5 | 6 | + |\n\
|___|___|___|___|\n\
| 7 | 8 | 9 | - |\n\
|___|___|___|___|\n\
|     0     | * |\n\
|___________|___|\n");
}
----------------------------------------------------------------------
18. Face

#include<stdio.h>
void main()
{
puts("________________");
puts("|   XXXXXXXXX  |");
puts("|   ( ^   ^ )  |");
puts("|   ( 0   0 )  |");
puts("|    \\  |  /   |");
puts("|     \\ = /    |");
puts("|      \\_/     |");
puts("|       |      |");
puts("|_______|______|\n");
}
----------------------------------------------------------------------
19. Addition of 2x2 Matrix

#include<stdio.h>
int main()

{
float a,b,c,d,e,f,g,h,i,j,k,l;

printf("\nSample of Ist matrix: | a=1      b=2 |\n                      | c=3      d=4 |\n\n\
Sample of 2nd matrix: | e=5      f=6 |\n                      | f=7      h=8 |\n\n");

        printf("Enter The Valve of a: ");
        scanf("%f",&a);
        printf("Enter The Valve of b: ");
        scanf("%f",&b);
        printf("Enter The Valve of c: ");
        scanf("%f",&c);
        printf("Enter The Valve of d: ");
        scanf("%f",&d);
        printf("Enter The Valve of e: ");
        scanf("%f",&e);
        printf("Enter The Valve of f: ");
        scanf("%f",&f);
        printf("Enter The Valve of g: ");
        scanf("%f",&g);
        printf("Enter The Valve of h: ");
        scanf("%f",&h); 
        
        i = a+e;
        j = b+f;
        k = c+g;
        l = d+h;
        printf("\n\nSum of Matrix(A+B) is: | %.2f     %.2f |\n                       | %.2f     %.2f |",i,j,k,l);
        
        i = a-e;
        j = b-f;
        k = c-g;
        l = d-h;
        printf("\n\nSubstraction of Matrix(A-B) is: | %.2f     %.2f |\n                                | %.2f     %.2f |",i,j,k,l);
        
        i = e-a;
        j = f-b;
        k = g-c;
        l = h-d;
        printf("\n\nSubstraction of Matrix(B-A) is: | %.2f     %.2f |\n                                | %.2f     %.2f |",i,j,k,l);
        
        return 0;
}
----------------------------------------------------------------------
20. Multiplication of 2x2 Matrix

#include<stdio.h>
int main()
{
float a,b,c,d,e,f,g,h,i,j,k,l;

printf("\nSample of Ist matrix: | a=1      b=2 |\n                      | c=3      d=4 |\n\n\
Sample of 2nd matrix: | e=5      f=6 |\n                      | f=7      h=8 |\n\n");

        printf("Enter The Valve of a: ");
        scanf("%f",&a);
        printf("Enter The Valve of b: ");
        scanf("%f",&b);
        printf("Enter The Valve of c: ");
        scanf("%f",&c);
        printf("Enter The Valve of d: ");
        scanf("%f",&d);
        printf("Enter The Valve of e: ");
        scanf("%f",&e);
        printf("Enter The Valve of f: ");
        scanf("%f",&f);
        printf("Enter The Valve of g: ");
        scanf("%f",&g);
        printf("Enter The Valve of h: ");
        scanf("%f",&h);

        i=(a*e)+(b*g);
        j=(a*f)+(b*h);
        k=(c*e)+(d*g);
        l=(c*f)+(d*h);

        printf("\nMultiplication of A,B is: | %.2f     %.2f |\n                          | %.2f     %.2f |",i,j,k,l);

        return 0;
}
----------------------------------------------------------------------
21. FizzBuzz loop

#include<stdio.h>
int main()
{
        int n,x;
        printf("\nEnter The Integer: ");
        scanf("%d",&n);
        printf("\n");

  {
        for(x=1;x<=n;x++)
        if(x%15==0)
        printf("FizzBuzz\n");
        else if(x%3==0)
        printf("Fizz\n");
        else if(x%5==0)
        printf("Buzz\n");
        else
        printf("%d\n",x);
  }

        return 0;
}
----------------------------------------------------------------------
