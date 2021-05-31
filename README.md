//Character-Constant
//This program is an example o understand Character Constant and their uses in C.

#include <stdio.h>

#define LENGTH 5  
#define WIDTH  5
#define NEWLINE '\n'

int main() {

   int area;  
  
   area = LENGTH * WIDTH;
   printf("value of area : %d", area);
   printf("%c", NEWLINE);

   return 0;
}
