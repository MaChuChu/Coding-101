
# Beginning of C Programming

## Structure of C
```C
#include <stdio.h>

main(){
  int a = 10;
  printf*("%d",a);
  return 0;
}
```
| **Header Files Inclusion** | #include <....>                                              |
| :------------------------- | ------------------------------------------------------------ |
| stddef.h                   | Defines several useful types and macros.                     |
| stdint.h                   | Defines exact width integer types.                           |
| stdio.h                    | Defines core input and output functions.                     |
| stdlib.h                   | Defines numeric conversion functions, pseudo-random network generator, memory allocation. |
| string.h                   | Defines string handling functions.                           |
| math.h                     | Defines common mathematical functions.                       |

## Main Method Decleration

### Syntax for Declaring main method
```C
int main(){
   return 0;
}
```
## Variable Declaration
Variables need to be declared to be used within the program.
```C
main(){
  int a;
}
```

## Body
Operations are performed within the body.
```C
main(){
  int a = 10; //Declaring variable
  printf*("%d",a); //Output text into terminal
  return 0;
}
```

## Return Statement
The return statement refers to the returning of the values from a function.  
This return statement and return value depend upon the return type of the function.
```C
main(){
  return 0;
}
```
