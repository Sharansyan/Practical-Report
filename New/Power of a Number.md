
# Power of a Number
```C
     #include<stdio.h>
     int main()
     {
     int base,exp;
     int result=1;
     printf("\nEnter base number\n");
     scanf("%d",&base);
     printf("Enter exponent");
     scanf("%d",&exp); 
     while (exp!=0)
     {
     result *=base;
     exp--;
     }
     printf("awnser=%d\n", result);
     return 0;
     }
     ```
## Output
   
     Enter base number
     2
     Enter exponent5
     awnser=32
