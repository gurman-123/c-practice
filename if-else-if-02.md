# Task : Largest of Three Numbers

###  Problem:

Declare three integers:
`int a = 10, b = 25, c = 15;`

Use `if-else if` to print the largest number.

---

# Source Code

```

#include <stdio.h>

int main(){
	int a=10;
	int b=25;
	int c=15;
	if (a >= b && a >= c) 
	{
        printf ("a is the largest number.");
    }
	 else if (b >= a && b >= c) 
	{
        printf (" b is the largest number.");
    } 
	else 
	{
        printf ("c is the largest number.");
    }
}

```

---

# Output

```
 b is the largest number.
```
