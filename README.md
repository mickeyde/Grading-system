#include <stdio.h>


void main() 
{
    int mark;
    
 printf("enter mark: ");
 scanf("%d", & mark);
 
 if (mark >=70 && mark <=100)
 { 
     printf("your grade is: A");
 }
 else if(mark >=60 && mark <=69 )
 {
    printf("your grade is: B");
 }
else if(mark >=50 && mark <=59 )
{
    printf("your grade is: C");
}
else if(mark >=40 && mark <=49 )
{
    printf("your grade is: D");
}
else 
{
    printf("your grade is: F");
}
 
 
}
