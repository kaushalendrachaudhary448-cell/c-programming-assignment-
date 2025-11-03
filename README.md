
# C-programming-
Programming 
Questions.1
#include <stdio.h>
int main() {
    int numbers[5] = {10, 20, 30, 40, 50}; // Declaration and initialization
    printf("First element: %d\n", numbers[0]);
    printf("Third element: %d\n", numbers[2]);
    return 0;
}
output 
First element: 10
Third element: 30
Questions.2
(a)
#include <stdio.h>
int main() {
    printf("Hello World");
    return 0;
}
output 
Hello World
(b)
#include <stdio.h>
void greet() {                 
    printf("Welcome to C Programming");
}
int main() {
    greet();                  
    return 0;
}
output 
Welcome to C Programming!
Questions.3
#include <stdio.h>
int main() {
    int x = 10;
    int *ptr;      
    ptr = &x;      
    printf("Value of x: %d\n", x);
    printf("Address of x: %p\n", ptr);
    printf("Value at pointer: %d\n", *ptr);
    return 0;
}
output 
Value of x: 10
Value at pointer: 10
Questions.4
#include <stdio.h>
int main() {
    int marks[3] = {85, 90, 95}; // 1D Array
    printf("1D Array:\n");
    for(int i = 0; i < 3; i++) {
        printf("%d ", marks[i]);
    }
    int matrix[2][2] = {{1, 2}, {3, 4}}; // 2D Array
    printf("\n\n2D Array:\n");
    for(int i = 0; i < 2; i++) {
        for(int j = 0; j < 2; j++) {
            printf("%d ", matrix[i][j]);
        }
        printf("\n");
    }
    return 0;
}
output 
1D Array:
85 90 95 
2D Array:
1 2 
3 4
Questions.5
#include <stdio.h>
int main() {
    int a = 10, b = 5;
    // Arithmetic
    printf("Sum: %d\n", a + b);
    // Relational
    printf("Is a greater than b? %d\n", a > b);
    // Logical
    printf("Both positive? %d\n", (a > 0 && b > 0));
    // Assignment
    a += 2;
    printf("After assignment: %d\n", a);
    // Increment
    b++;
    printf("After increment: %d\n", b);
    // Ternary
    int max = (a > b) ? a : b;
    printf("Greater value: %d\n", max);
    return 0;
}
output 
Sum: 15
Is a greater than b? 1
Both positive? 1
After assignment: 12
After increment: 6
Greater value: 12

