---
tags:
  - C
  - Arrays
  - ComputerScience
---
## Declaring Arrays
``` c
dataType arr[size];
```

## Declaring Array's without Size
[[Dynamic Memory Allocation - C]]

## Setting Entire Array to One Value
- Set the value of the array by using curly brackets {0}
- The array now contains 100 zero's

``` cpp
#include <stdio.h>

int main () {
	int AllZero[100] = {0};
}
```

## Initializing Array With Set Values
```c
char chars[] = {'a','b','c','d','e'};
```
An array can also be initialized without a **size**, if you set values.
**NOTE:** This is not good practice, and should be avoided

# See Also
[[Pointers and Arrays - C]]