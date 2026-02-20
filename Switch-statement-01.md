## Task  — Day of Week

Write a C program that takes a number (1–7) and prints the corresponding day of the week using a `switch` statement.

**Example:**
Input: `3`
Output: `Wednesday`

---

## Source code
```
#include <stdio.h>

int main(){
	int day=3;
	switch (day){
		case 1:
			printf("Monday");
			break;
		case 2:
		    printf("Tuesday");
			break;
		case 3:
			printf("Wednesday");
			break;
		case 4:
			printf("Thursday");	
			break;
		case 5:
			printf("Friday");
			break;
		default:
		    printf("Weekend");				
	}
}
```

---

## Output
```
Wednesday
```
