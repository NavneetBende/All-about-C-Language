#include <stdio.h>

int main()
{
  const int x = 5;
  
  int *ptr = &x; // non-const pointer pointing to a const variable
  *ptr = 10;
  
  // The below assignment is invalid in C++,results in error.
  // In C, the compiler may throw a warning, but casting is implicitly allowed
  printf ("x = %d\n", x);
  
  return 0;
}
