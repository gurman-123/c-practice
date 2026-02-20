##  Task  — Grade System

Write a program that prints grade description using `switch`:

| Grade | Output    |
| ----- | --------- |
| A     | Excellent |
| B     | Very Good |
| C     | Good      |
| D     | Pass      |
| F     | Fail      |

---

## Source code
```
#include <stdio.h>

int main() {
    char grade='A';
    switch (grade) {
        case 'A':
            printf("Excellent");
            break;
        case 'B':
            printf("Very Good");
            break;
        case 'C':
            printf("Good");
            break;
        case 'D':
            printf("Pass");
            break;
        default:
            printf("Fail");
    }
}
```

## Output
```
Excellent
```
