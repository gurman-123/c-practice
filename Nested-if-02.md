# Task : Find Largest of Three Numbers (Using Nested if)

###  Problem:

Declare:

```c
int a = 10, b = 20, c = 15;
```

Use nested `if` to find the largest number.

---

## Source code
```
#include <stdio.h>

int main(){
	int a=10;
	int b=20;
	int c=15;
	if(b>a)
	{
		if(b>c)
		  {
			printf("b is greater than a and c");
        	}
        else{
        	printf("b is greater than c but smaller than a");
		}	

	}
	else{
		printf("a is smaller than b and c");
	}
}
```

---

## Output
```
b is greater than a and c
```
