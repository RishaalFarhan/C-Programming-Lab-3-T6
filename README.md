# C-Programming-Lab-3-T6
Creating and Formatting markdown elements.

# Lab 4 Task 6 - Largest Number 
This is written to **determine the largest number** among *three numbers* and this ~~also~~ includes markdown styles.

## Code

---

## 📌 How It Looks on GitHub

# Lab 04 - Largest Number Program  

This is **bold text**, this is *italic text*, and this is ~~strikethrough text~~.  

## Example Code  
Written on **dev c++**.
Programming Language *used* is **C**.
 

#include <stdio.h>
'''c
int main() {
    int a, b, c;
    printf("Enter three numbers: ");
    scanf("%d %d %d", &a, &b, &c);

    if(a >= b && a >= c) {
        printf("%d is the largest \n", a);
    } else if(b >= a && b >= c) {
        printf("%d is the largest \n", b);
    } else {
        printf("%d is the largest \n", c);
    }

    return 0;
}

### Task List
- [x] Write C Program to determine largest number.
- [ ] Test program with different inputs.
- [ ] Comments to explain code.
- [x] Use Markdown formatting in README.



