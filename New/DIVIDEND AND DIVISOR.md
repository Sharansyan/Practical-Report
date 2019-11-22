# PROGRAM TO FIND DIVIDEND AND DIVISOR
  ```C 
   #include <stdio.h>
    double main()
    {
    int a,b;
    double c,d;
    printf("enter dividend=",a);
    scanf("%d",&a);
    printf("enter divisor=",b);
    scanf("%d",&b);
      c=a/b;
    printf("\n quotient=%0.2f\n",c);
      d=a % b;
   printf("reminder=%0.2f\n",d);
   return 0;
   }
   ```
   ## Output
   
           enter dividend=124
        enter divisor=12

         quotient=10.00
         reminder=4.00
