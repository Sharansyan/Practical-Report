![College Logo](https://www.gndec.ac.in/logo.png)

# **PROGRAMMING FOR PROGRAM SOLVING ESC-18105**
## **NAME - SHARANJIT SINGH**
## **ROLL NO - 1914103**
## **SECTION - CE(B2)**
----------------------------------------------

# INDEX
1. Program to find Sum
2. Program to print Hello World
3. Program to print a Table
4. Program to find Area, Perieter, Volume of a Circle
5. Program to find Area, Perimeter of a Rectangle
6. Program to find Interest
7. Program to find Maximum
8. Program to find a Power of a Number
9. Program To find Minimum
10. Program to take 5 values from the user and store them in an array and Print the elements stored in the array
11. Program to use Arithmetic Operators
12. Program to use Assignment Operators
13. Program to use Operator Precedence
14. Program to find Average
15. Program to print Fibbonacci Series
16. Program to find FizzBuzz od a Integer
17. Program swap two numbers using call by value
18. Program swap two numbers using call by reference
19. Program of Addition of 2x2 Matrix
20. Program of Multiplication of 2x2 Matrix
21. Program of FizzBuzz in a continues loop
22. Program to find Sum by using function
23. Program to print a Pyramid
24. Program to implement Linear search for One Dimensional array
25. Program to implement linear search with desirable values
26. Program to implement Binary search with desirable values
27. Program to find Prime number
28. Program of days of the week
29. Program to print Even numbers using while loop
30. Program of Volume(Different Shapes)
31. Program to find Sum of A.P series
32. Program to multiply Two Floating Point Numbers
33. Program to find weather the Number is Even or Odd using if-else statement
34. Program to find Sum of First 10 Natural Numbers using for loop
35. Program to print Odd numbers using do while loop
36. Program of a Simple Calculator
37. Program to implement Bubble Sort
38. Program to find Factorial
39. Program to Store Information of a Student using Structure
40. Program to find Multiplication of Matrix using array

###  1. Program to find Sum

```C
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
```  

### Output of the program

    Enter The First Numder: 45.26

    Enter The Second Numder: 78.2648

    Answer is: = 123.525
   
###  2. Program to print Hello World

```C
    #include<stdio.h>
    void main()
    {
         puts("\nHello World\n");
    }
```

### Output of the program

    Hello World

###  3. Program to print a Table

```C
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
```

### Output of the program

    73.00 x 1 = 73.000
    73.00 x 2 = 146.000
    73.00 x 3 = 219.000
    73.00 x 4 = 292.000
    73.00 x 5 = 365.000
    73.00 x 6 = 438.000
    73.00 x 7 = 511.000

###  4. Program to find Area, Perieter, Volume of a Circle

```C
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
```

### Output of the program

    Enter The Radius of Circle: 4.5

    Perimeter of Circle is: = 28.29
    Area of Circle is: = 63.64
    Volume of Circle is: = 381.86

###  5. Program to find Area, Perimeter of a Rectangle

```C
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
```

### Output of the program

    Enter Height: 24

    Enter Bredth: 60

    Area of Sqare (or) Rectangle: = 1440.000
    Perimeter of Sqare (or) Rectangle: = 168.000

###  6. Program to find Interest

```C
    #include<stdio.h>
    int main()
    {
         float P,R,T,Interest;
         printf("\nEnter The Principal Amount: ");
         scanf("%f", &P);

         printf("\nEnter The Interest Rate: ");
         scanf("%f", &R);
        
         printf("\nEnter The Time (in months): ");
         scanf("%f", &T);

         Interest = P*T*R/100;
        
         printf("\nSimple Intesest is: = %.2f", Interest);
         return Interest;
    }
```

### Output of the program

    Enter The Principal Amount: 4000

    Enter The Interest Rate: 4

    Enter The Time (in months): 3

    Simple Intesest is: = 480.00

###  7. Program to find Maximum

```C
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
```

### Output of the program

    Enter The First Value: 5

    Enter The Second Value: 4

    Maximum value is: 5.00

###  8. Program to find a Power of a Number

```C
#include<stdio.h>
int main()
{
  int base,power,ans=1;
  printf("\nEnter base number: ");
   scanf("%d",&base);
  printf("Enter exponent(power): ");
   scanf("%d",&power);

while (power!=0)
 {  ans *= base;
    power--;  }

  printf("Answer = %d\n", ans);
return 0;
}
```

### Output of the program

    Enter base number: 5
    Enter exponent(power): 4
    Answer = 625

###  9. Program To find Minimum

```C
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
```

### Output of the program

    Enter The First Value: 5

    Enter The SecondValue: 3

    Minimum value is: 3.00

### 10. Program to take 5 values from the user and store them in an array and Print the elements
### stored in the array

```C
     #include<stdio.h>
     int main()
     {
       int x,array[5];
       printf("\n");
       
       for(x=1;x<=5;x++)
       {  printf("Enter [%d] element: ", x);
          scanf("%d", &array[x]);  }
          
       for(x=1;x<=5;x++)
       {  printf("\nElement [%d] = %d", x, array[x]);  }

     return 0;
     }
```

### Output of the Program

     Enter [1] element: 4
     Enter [2] element: 5
     Enter [3] element: 6
     Enter [4] element: 9
     Enter [5] element: 2

     Element [1] = 4
     Element [2] = 5
     Element [3] = 6
     Element [4] = 9
     Element [5] = 2

###  11. Program to use Arithmetic Operators

```C
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
```

### Output of the program

    Enter The Value of x: 45

    Enter The Value of y: 31
    x + y = 76.000
    x - y = 14.000
    y - x = -14.000
    x * y = 1395.000
    x/y = 1.452
    y/x = 0.689

###  12. Program to use Assignment Operators

```C
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
```

### Output of the program

    Enter The Value of x: 45
    Answer is a = x 45.000
    Answer is a+x = 90.000
    Answer is a-x = 45.000
    Answer is a*x = 2025.000
    Answer is a/x= 45.000

###  13. Program to use Operator Precedence

```C
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
         printf("\n (b-c)*(a-d) = %.3f",A);

         return 0;
    }
```

### Output of the program

    Enter The Value of a: 45
    Enter The Value of b: 31
    Enter The Value of c: 18
    Enter The Value of d: 71

    (a+b)*(c+d) = 6764.000
    (c+d)*a*b = 124155.000
     a*d/(c-b-a) = -55.086
    (b-c)*(a-d) = -338.000

###  14. Program to find Average

```C
     #include<stdio.h>
     int main()
     {
     int x,N;
     float avg[1000],s,ans;

     printf("\nEnter the Number of elements: ");
     scanf("%d", &N);
     printf("\n");

     for(x=1; x<=N; x++)
       {  printf("Enter [%d] element: ", x);
          scanf("%f", &avg[x]);
          s += avg[x];  }
  
       ans = s/N;

     printf("\nAverage of %d elements = %.3f", N, ans);
     return 0;
     }
```

### Output of the program

     Enter the Number of elements: 8

     Enter [1] element: 1
     Enter [2] element: 2
     Enter [3] element: 3
     Enter [4] element: 4
     Enter [5] element: 5
     Enter [6] element: 6
     Enter [7] element: 7
     Enter [8] element: 8
     
     Average of 8 elements = 4.500    

###  15. Program to print Fibbonacci Series

```C
#include<stdio.h>
int fibbo(int f);

int main()                                                                      
{
   int x,i,f=0;
   printf("\nEnter fibbonacci Number: ");
   scanf("%d", &x);

   for(i=1; i<=x; i++)
     {  printf("%d\n", fibbo(f));
        f++;  }
return 0;
}

int fibbo(int f)
  {  if(f==1 || f==0)
     return f;
     else
     return ( fibbo(f-1) + fibbo(f-2) );  }
```

### Output of the program

    Enter fibbonacci Number: 10
    0
    1
    1 
    2    
    3    
    5    
    8
    13
    21
    34

###  16. Program to find FizzBuzz od a Integer

```C
    #include<stdio.h>
    int main()
    {
         int n;
         printf("\nEnter the Interger: ");
         scanf("%d",&n);

         if(n%15==0)
         printf("\nFizzBuzz");
         else if(n%3==0)
         printf("Fizz\n");
         else if (n%5==0)
         printf("\nBuzz");
         else
         printf("\n%d",n);
         return 0;
    }
```

### Output of the program

    Enter the Interger: 171
    Fizz

###  17. Program swap two numbers using call by value 

```C
    #include <stdio.h>
    int main()
    {
      int x, y, t;
      printf("\n\nEnter two integers: ");
      scanf("%d %d", &x, &y);
      printf("\n\nBefore Swapping: \nFirst integer = %d\nSecond integer = %d\n", x, y);
      t = x;
      x = y;
      y = t;
      printf("\n\nAfter Swapping: \nFirst integer = %d\nSecond integer = %d\n", x, y);
      return 0;
    }
```

### Output of the program

    Enter two integers: 1  56

    Before Swapping:
    First integer = 1
    Second integer = 56

    After Swapping:
    First integer = 56
    Second integer = 1

###  18. Program swap two numbers using call by reference

```C
#include <stdio.h>
void swap(int*, int*);

   int main()
   {  int x, y;
      printf("\nEnter the two integers: ");
      scanf("%d %d", &x, &y);
      printf("\nBefore Swapping\nx = %d\ny = %d", x, y);
      
      swap(&x, &y);
      printf("\nAfter Swapping\nx = %d\ny = %d", x, y);
      return 0;  }
      
   void swap(int *a, int *b)
   {  int temp;
      temp = *b;
      *b = *a;
      *a = temp;  }
```

### Output of the program

     Enter the two integers: 45 98

     Before Swapping
     x = 45
     y = 98
     After Swapping
     x = 98
     y = 45

###  19. Program of Addition of 2x2 Matrix

```C
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
```

### Output of the program

    Sample of Ist matrix: | a=1      b=2 |
                          | c=3      d=4 |

    Sample of 2nd matrix: | e=5      f=6 |
                          | f=7      h=8 |

    Enter The Valve of a: 7
    Enter The Valve of b: 5
    Enter The Valve of c: 4
    Enter The Valve of d: 0
    Enter The Valve of e: 3
    Enter The Valve of f: 5
    Enter The Valve of g: 9
    Enter The Valve of h: 1


    Sum of Matrix(A+B) is: | 10.00     10.00 |
                           | 13.00     1.00 |

    Substraction of Matrix(A-B) is: | 4.00     0.00 |
                                    | -5.00     -1.00 |

    Substraction of Matrix(B-A) is: | -4.00     0.00 |
                                    | 5.00     1.00 |

###  20. Program of Multiplication of 2x2 Matrix

```C
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
```

### Output of the program

    Sample of Ist matrix: | a=1      b=2 |
                          | c=3      d=4 |

    Sample of 2nd matrix: | e=5      f=6 |
                          | f=7      h=8 |

    Enter The Valve of a: 7
    Enter The Valve of b: 5
    Enter The Valve of c: 4
    Enter The Valve of d: 0
    Enter The Valve of e: 3
    Enter The Valve of f: 5
    Enter The Valve of g: 9
    Enter The Valve of h: 1

    Multiplication of A,B is: | 66.00     40.00 |
                              | 12.00     20.00 |

###  21. Program of FizzBuzz in a continues loop

```C
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
```
### Output of the program

    Enter The Integer: 17

    1
    2
    Fizz
    4
    Buzz
    Fizz
    7
    8
    Fizz
    Buzz
    11
    Fizz
    13
    14
    FizzBuzz
    16
    17
    
### 22. Program to find Sum by using function

```C
      #include<stdio.h>
      int ans(float a, float b);
      int main()
      {
          float a, b, ans;
          printf("\nEnter The Value of a: ");
          scanf("%f",&a);
          printf("Enter The Value of b: ");
          scanf("%f",&b);
          ans = (a*b);
          printf("Answer is: %.2f", ans);
          return 0;
      }
      int ans(float a, float b)
         {
          return a*b;
         }
```         
### Output of the program

      Enter The Value of a: 4
      Enter The Value of b: 5
      Answer is: 20.00
      
### 23. Program to print a Pyramid

```C
     #include<stdio.h>
     int main()
     {
     int i,j,n;
     printf("\nEnter number of Rows: ");
     scanf("%d",&n);
     printf("\n");
     
     for(i=1; i<=n; i++)
     {
         for(j=1; j<=2*n-1; j++)
         {
         if(j>=n-(i-1) && j<=n+(i-1))
         printf("*");
         else
         printf(" ");
         }
         printf("\n");
         }
         return 0;
     }
```

### Output of the program

     Enter number of Rows: 6
     
          *  
         ***    
        *****   
       *******  
      ********* 
     ***********
   
### 24. Program to implement Linear search for One Dimensional array

```C
    #include<stdio.h>
    int main()

    {
    int array[12]={1,5,9,7,3,82,46,23,23,5,10,3};
    int size=12,flag=0,item,a;

    printf("\nEnter the Value: ");
    scanf("%d", &a);

    for(int i=0;i<size;i++)
      {
        if(a==array[i])
          {
                flag=a;
                break;
          }
      }
      
        if(flag==a)
        printf("\nSearch is Sucessfull \n%d Element is present in the array\n",a);
        else
        printf("\nSearch is Unsucessfull \n%d Element is not present in the array\n",a);
        
        return 0;
    }
```
### Output of the program

    First Case

    Enter the Value to be searched: 5

    Search is Sucessfull 5 Element is present in the array
    
    Second Case
    
    Enter the Value to be searched: 2

    Search is Unsucessfull 2 Element is not present in the array
    

### 25. Program to implement linear search with desirable values

```C
    #include<stdio.h>
    int main()
    {

    int array[100],search,i,n;
    printf("\nEnter the Number of elements in array: ");
    scanf("%d",&n);
    printf("\n");

      for(i=1;i<=n;i++)
      {  printf("Enter [%d] element: ",i);
         scanf("%d",&array[i]);  }
      
    printf("\nEnter a number to search: ");
    scanf("%d",&search);

       for(i=0;i<=n;i++)
       {
          if(array[i]==search)         //if element is found
          {  printf("\n%d is present at location %d\n",search,i);
             break;   }
          else if(i>=n)
          {  printf("\n%d is not present in the array\n",search);  }

       }

    return 0;
    }
```
### Output of the Program

    Enter the Number of elements in array: 5

    Enter [1] element: 1
    Enter [2] element: 2
    Enter [3] element: 3
    Enter [4] element: 4
    Enter [5] element: 5

    Enter a number to search: 8

    8 is not present in the array
 
### 26. Program to implement Binary search with desirable values

```C
    #include<stdio.h>
    int main()
    {
    int n,i,s,f,m,l,a[100];  //a= array, n= size of array, s= element to be searched
                             //f= first element position, l= last element position
                             //m= mid element position
    printf("\nEnter the size of array: ");
    scanf("%d",&n);
    printf("\n");


    for(i=1;i<=n;i++)
    {  printf("Enter [%d] element: ",i);
       scanf("%d",&a[i]);   }

    printf("\nEnter the element you wants to search: ");
    scanf("%d",&s);

    f=0;
    l=n-1;
    m=(f+l)/2;


    while(f<=l)
    {
          if (a[m]<s)
          {  f=m+1;  }
          else if(a[m]==s)
          {  printf("Location of given %d is %d \n",s,m);
             break;  }
          else
          {  l=m-1;  }
          m=(f+l)/2;              
    }

    if(f>l)
    printf("%d is not found in the array\n",s);
  
    return 0;
    }
```
### output of the Program

    Enter the size of array: 7
      
    Enter [1] element: 5
    Enter [2] element: 2
    Enter [3] element: 8
    Enter [4] element: 49
    Enter [5] element: 657
    Enter [6] element: 32
    Enter [7] element: 0
  
    Enter the element you wants to search: 5
    Location of given 5 is 1 
   
### 27. Program to find Prime number

```C
      #include<stdio.h>
      int main()
      { 
      int a;
      printf("\nEnter the Number: ");
      scanf("%d",&a);

       for(int x=1;x<a;x++)
       { 
         if(a%x!=0)
         {  printf("%d is a Prime Number",a);
            break;  }
         else
         {  printf("%d is not a Prime Number",a);
            break;  }
        }
      return 0;
      }
```

### Output of the program

      Enter the Number: 7
      7 is not a Prime Number

      Enter the Number: 8
      8 is not a Prime Number
 
### 28. Program of days of the week 

```C
     #include<stdio.h>
     int main()
     {

     int x;
     printf("\n\nEnter the day Number: ");
     scanf("%d", &x);

     switch(x)
     {
       case 1:
       if(x==1)
       {  printf("\nSunday");  }
       case 2:
       if(x==2)
       {  printf("\nMonday");  }
       case 3:
       if(x==3)
       {  printf("\nTuesday");  }
       case 4:
       if(x==4)
       {  printf("\nWednesday");  }
       case 5:
       if(x==5)
       {  printf("\nThursday");  }
       case 6:
       if(x==6)
       {  printf("\nFriday");  }
           case 7:
       if(x==7)
       {  printf("\nSaturday");  
     } 

     return 0;
     }
 ```    
### Output of the Program

    Enter the day Number: 3

    Tuesday
  

### 29. Program to print Even numbers using while loop

```C
#include<stdio.h>
int main()
{
int x=1,N;
printf("\n\nEntere the Integer: ");
scanf("%d", &N);

   while(x<=N)
   {
     if(x%2==0)
     printf("\n%d", x);
     else
     printf("");
     x++;
   }
return 0;
}
```

### Output of the Program

     Entere the Integer: 10

     2
     4
     6
     8  
     10
  
### 30 Program of Volume(Different Shapes)

```C
    #include<stdio.h>
    int main()
    {
    int a;                             //a = Code of the shape     
    float sphere,Sr,pi=22.0/7.0;       //Cr = radius of circle, sphere = volume (Sphere)
    float Cs,cube;                     //Cs = side, cude = volumre (cube)
    float Rl,Rb,Rh,rectangle;          //Rl = length, Rb = breadth, Rh = Heigth, rectangle = volume (Rectangle)
    float Cr,Ch,cylinder;              //Cr = Radius, Ch = Height, cylinder = Volume (cylinder)
    float CoR,CoH,cone;                //CoR = Radius, CoH = Height, cone = Volume (Cone)

    printf("\n\nPress 1 (Sphere) \nPress 2 (Cube) \nPress 3 (Rectangle) \n\
    Press 4 (Cylinder) \nPress 5 (Cone) \n\nEnter the shape,you wants to find the volume: ");
    scanf("%d", &a);

    switch(a)
    {
    case 1:
      if(a==1)
      { printf("\nEnter the radius of Sphere: ");
      scanf("%f", &Sr);
      sphere = 4*pi*Sr*Sr*Sr/3;
      printf("Volume of Shpere = %.4f", sphere);
      break;  }

    case 2:
      if(a==2)
      { printf("\nEnter the Side of Cube: ");
      scanf("%f", &Cs);
      cube = Cs*Cs*Cs;
      printf("Volume of Cube = %.4f", cube);
      break;  }
        
    case 3:
      if(a==3)
      {  printf("\nEnter the length of Rectangle: ");
      scanf("%f", &Rl);
      printf("Enter the breadth of Rectangle: ");
      scanf("%f", &Rb);
      printf("Enter the Height of Rectangle: ");
      scanf("%f", &Rh);
      rectangle = Rl*Rb*Rh;
      printf("Volume of Rectangle = %.4f", rectangle);
      break;  }
        
    case 4:
      if(a==4)
      {  printf("\nEnter the Radius of Cylinder: ");
      scanf("%f", &Cr);
      printf("Enter the Height of Cylinder: ");
      scanf("%f", &Ch);
      cylinder = pi*Cr*Cr*Ch;
      printf("Volume of Cylinder = %.4f", cylinder);
      break;  }
        
    case 5:
      if(a==5)
      {  printf("\nEnter the Radius of Cone: ");
      scanf("%f", &CoR);
      printf("Enter the Height of Cone: ");
      scanf("%f", &CoH);
      cone = pi*CoR*CoR*CoH/3;
      printf("Volume of Cone = %.4f", cone);
      break;  }
        
    } 
    return 0;
    
    } 
```
### output of the Program 

    Press 1 (Sphere) 
    Press 2 (Cube) 
    Press 3 (Rectangle) 
    Press 4 (Cylinder) 
    Press 5 (Cone)                                                            

    Enter the shape,you wants to find the volume: 1
    Enter the radius of Sphere: 10
    Volume of Shpere = 4190.4761 

    Enter the shape,you wants to find the volume: 2
    Enter the Side of Cube: 17.5   
    Volume of Cube = 5359.3750

    Enter the shape,you wants to find the volume: 3
    Enter the length of Rectangle: 11
    Enter the breadth of Rectangle: 12
    Enter the Height of Rectangle: 13
    Volume of Rectangle = 1716.0000

    Enter the shape,you wants to find the volume: 4
    Enter the Radius of Cylinder: 7
    Enter the Height of Cylinder: 8
    Volume of Cylinder = 1232.0000

    Enter the shape,you wants to find the volume: 5
    Enter the Radius of Cone: 2
    Enter the Height of Cone: 1.5
    Volume of Cone = 6.2857


### 31. Program to find Sum of A.P series

```C
    #include<stdio.h>
    int main()
    {   
    int N,x;                //N = length of the series, x = second term or difference
    float a1,a2,d,S;        //a1 = first or last term
                            //a2 = second term, d = differenc
                            //S = sum of the terms
    printf("\n\nEnter N of the series: ");
    scanf("%d", &N);
    printf("Enter first or last term of the series: ");
    scanf("%f", &a1);

    printf("\nEnter 1 for Second term, Enter 2 for difference\n\nEnter 1 or 2: ");
    scanf("%d", &x);


    if(x==1)
      {  printf("\nEnter the second term: ");
         scanf("%f", &a2);
         d = a2-a1;
         S = N*(2*a1 + (N-1)*d) /2;
         printf("\nSum of given series = %.2f", S);  }

    else if(x==2)
      {  printf("\nEnter the Difference: ");
         scanf("%f", &d);
         S = N*(2*a1 + (N-1)*d) /2;
         printf("\nSum of given series = %.2f", S);  }

    else
      printf("\nEnter a valid input(1 or 2)");
    return 0;
    }
```  
### Output of the Program 

    Enter N of the series: 10
    Enter first or last term of the series: 2

    Enter 1 for Second term, Enter 2 for difference

    Enter 1 or 2: 1

    Enter the second term: 6

    Sum of given series = 200.00

### 32. Program to multiply Two Floating Point Numbers

```C
     #include<stdio.h>
     int main()
     {
     float x,y,ans;
       printf("\n\nEnter the First value: ");
       scanf("%f", &x);
       printf("Enter the Second value: ");
       scanf("%f", &y);

       ans = x*y;

       printf("\nAnswer = %.3f",ans);
     return 0;
     }
```

### Output of the Program

     Enter the First value: 1.2
     Enter the Second value: 3.2
  
     Answer = 3.840
     
### 33. Program to find weather the Number is Even or Odd using if-else statement

```C
     #include<stdio.h>
     int main()
     {
     int x;
       printf("\n\nEnter the Number: ");
       scanf("%d", &x);

       if(x%2==0)
       printf("%d is Even", x);
       else
       printf("%d is Odd", x);
     return 0;
     }
```

### Output of the Program

     Enter the Number: 6
     6 is Even

     Enter the Number: 9
     9 is Odd
     
### 34. Program to find Sum of First 10 Natural Numbers using for loop

```C
#include<stdio.h>
int main()
{
int x,ans;
  for(x=1;x<=10;x++)
  {  ans += x; }

  printf("\n\nSum of first 10 Nmubers: %d",ans);
return 0;
}
```

### Output of the Program

     Sum of first 10 Nmubers: 55

### 35. Program to print Odd numbers using do while loop
 
```C
     #include<stdio.h>
     int main()
     {
     int x=1,N;
     printf("\n\nEntere the Integer: ");
     scanf("%d", &N);
       do
        {
        if(x%2!=0)
        printf("\n%d", x);
        else
        printf("");
        x++;
        }
       while(x<=N);
     return 0;
     }
```

### Output of the Program

     Entere the Integer: 13

     1
     3
     5
     7
     9
     11
     13
     
### 36. Program of a Simple Calculator

```C
     include<stdio.h>
     int main()
     {
     char operator;
     float x,y;
     printf("\n\nEnter an operator (+, -, *, /): ");
     scanf("%c", &operator);
     printf("Enter two operands: ");
     scanf("%f %f", &x, &y);
     switch(operator)
     {
             case '+':
             printf("\n%.2f + %.2f = %.2f", x, y, x+y);
             break;
             case '-':
             printf("\n%.2f - %.2f = %.2f", x, y, x-y);
             break;
             case '*':
             printf("\n%.2f * %.2f = %.2f", x, y, x*y);
             break;
             case '/':
             printf("\n%.2f / %.2f = %.2f", x, y, x/y);
             break;
             default:
             printf("\nError! operator is not correct");
     }
     return 0;
     }
```
### Output of the Program

     Enter an operator (+, -, *, /): *
     Enter two operands: 146  21

     146.00 * 21.00 = 3066.00

### 37. Program to implement Bubble Sort

```C
#include <stdio.h>
int main()
{
  int array[100], n, c, d, swap;
  printf("Enter number of elements: ");
  scanf("%d", &n);
  printf("Enter %d integers\n", n);

  for (c=0; c<n; c++)
    scanf("%d", &array[c]);

  for (c=0; c<n-1; c++)
  {
    for (d=0 ; d<n-c-1; d++)
    {
      if (array[d] > array[d+1])
      {
        swap       = array[d];
        array[d]   = array[d+1];
        array[d+1] = swap;
      }
    }
  }

  printf("Sorted list in ascending order:\n");

  for (c=0; c<n; c++)
     printf("%d\n", array[c]);

  return 0;
}
```
### Output of the Program

    Enter number of elements: 6
    Enter 6 integers
    1     
    2      
    3       
    8       
    9     
    1   
    Sorted list in ascending order:
    1
    1 
    2
    3 
    8    
    9

### 38. Program to find Factorial 

```C
#include<stdio.h>
long factorial(int);

int main()
  {  int x;
     long fact = 1;
     printf("\nEnter a number to calculate it's factorial: ");
     scanf("%d", &x);
     printf("%d! = %ld\n", x, factorial(x));
     return 0;  }

long factorial(int x)
  {  int c;
     long ans=1;
     for (c=x; c>1; c--)
     {  ans *= c;  }
     return ans;
  }
```

### Output of the Program

     Enter a number to calculate it's factorial: 6
     6! = 720

     Enter a number to calculate it's factorial: 12
     12! = 479001600
     
### 39. Program to Store Information of a Student using Structure

```C
    #include<stdio.h>
    struct student
    {  char name[50];
       long int ph,marks;  };

    int main()
    {
      printf("\nEnter the information of student: \n");

      struct student s;
      printf("Enter Name: ");
       scanf("%s", &s.name);
      printf("Enter Phone Number: ");
       scanf("%ld", &s.ph);
      printf("Enter Marks: ");
       scanf("%d", &s.marks);

      printf("\nEntered Information is: \n");
  
      printf("Name: %s\n", s.name);
      printf("Age: %ld\n", s.ph);
      printf("Marks: %d\n", s.marks);

    return 0;
    }
```

### Output of the Program

    Enter the information of student: 
    Enter Name: Sharanjit
    Enter Phone Number: 9465329287
    Enter Marks: 86

    Entered Information is: 
    Name: Sharanjit
    Age: 9465329287
    Marks: 86

### 40. Program to find Multiplication of Matrix using array

```C
#include <stdio.h>
int main()
{
  
int a[10][10], b[10][10], result[10][10], r1, c1, r2, c2, i, j, k;
// a and b are 1st and 2nd matrix
// r1 and c1 is rows and column of 1st matrix respectively
// r2 and c2 is rows and column of 2nt matrix respectively
// result[10][10] is the multiplication of matrix 1 and 2

// Geting the value of rows and columns
  printf("\nEnter rows and column for first matrix: ");
  scanf("%d %d", &r1, &c1);
  printf("Enter rows and column for second matrix: ");
  scanf("%d %d", &r2, &c2);
    
// Column of first matrix should be equal to column of second matrix
  while (c1 != r2)                                                                                                                                                   
  {                                                                                                                                                                  
  printf("Error! Column of First Matrix is not equal to Row of Second Matrix.\n\n");                                                                                 
  printf("Enter Rows and Column for First Matrix: ");                                                                                                                
  scanf("%d %d", &r1, &c1);                                                                                                                                          
  printf("Enter Rows and Column for Second Matrix: ");                                                                                                               
  scanf("%d %d", &r2, &c2);
  }
  // Storing elements of second matrix.
  printf("\nEnter elements of matrix 2:\n");
  for(i=0; i<r2; ++i)
    for(j=0; j<c2; ++j)
    {
    printf("Enter elements b[%d][%d]: ",i+1, j+1);
    scanf("%d", &b[i][j]);
    }

  
// Initializing all elements of result matrix to 0
  for(i=0; i<r1; ++i)
    for(j=0; j<c2; ++j)
    {
    result[i][j] = 0;
    }
                                                                                                                                                                     // Multiplying matrices a and b and storing result in result matrix                                                                                                  
  for(i=0; i<r1; ++i)  
  for(j=0; j<c2; ++j)  
      for(k=0; k<c1; ++k)                                                                                                                                            
      {                                                                                                                                                              
      result[i][j] += a[i][k] * b[k][j];
      }
// Displaying the result
  printf("\nOutput Matrix:\n");
  for(i=0; i<r1; ++i)
    for(j=0; j<c2; ++j)
    {
    printf("%d  ", result[i][j]);
    if(j == c2-1)
    printf("\n\n");
    }   
return 0;                                                                                                                                                                   }     
```

### Output of the Program







