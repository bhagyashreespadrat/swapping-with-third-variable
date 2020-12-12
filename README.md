# swapping-with-third-variable
#swapping with third variable using temp
#include <stdio.h>
#swap two number using third variable
int main() {
   int x,y,temp;
   printf("\n enter valueof x and y:");
   scanf("%d%d",&x,&y);
   printf("Before swapping x=%d and y=%d\n",x,y);
   temp=x;
   x=y;
   y=temp;
    printf("After swapping x=%d and y=%d\n",x,y);
   
}
/*OUTPUT:
enter valueof x and y:10
 12
 Before swapping x=10 and y=12
After swapping x=12 and y=10


*/
