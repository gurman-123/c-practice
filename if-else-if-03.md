#  Task : Number Type Checker

###  Problem:

Declare `int num = 0;`

Use `if-else if` to check:

* If number is positive
* If number is negative
* Otherwise print `"Number is Zero"`
---

# Source Code

```
#include <stdio.h>

int main(){
	int num = 0;
	if (num <0)
	 {
	 	printf("Number is Negative");
	 }
	else if (num >0)
	{
		printf("Number is positive");
	 } 
	else 
	{
		printf("Number is zero");
	 } 
}

```

---

# Output

```
Number is zero
```
