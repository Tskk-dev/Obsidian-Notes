
---

### **Basic C Program Structure**

1. **Header Files**  
   - Contains pre-written functions used by the program.  
   - Example: `#include<stdio.h>`, includes the standard input/output library for functions like `printf()` and `scanf()`.

2. **Main Function**  
   - The entry point of every C program.  
   - Syntax:  
     ```c
     int main() {
         // Code here
         return 0;
     }
     ```

3. **Variable Declarations**  
   - Declare variables before using them in the program.  
   - Example: `int x;`, `float y;`, `char ch;`

4. **Input/Output Statements**  
   - **printf()**: Used to display output.  
      Example:  
       ```c
       printf("Hello, World!");
       ```
       **Output**:  
       ```
       Hello, World!
       ```
   
   - **scanf()**: Used to take input from the user.  
     - Example:  
       ```c
       int x;
       scanf("%d", &x);
       ```
       If the user inputs **5**, `x` will store **5**.

---

### **Data Types**

- **int**  
  - Represents whole numbers.  
  - Example: `int a = 10;`

- **float**  
  - Represents numbers with decimals.  
  - Example: `float pi = 3.14;`

- **char**  
  - Represents a single character.  
  - Example: `char letter = 'A';`

- **double**  
  - Represents larger floating-point numbers.  
  - Example: `double d = 3.141592;`

---

### **Operators**

1. **Arithmetic Operators**  
   - Used to perform basic mathematical operations.  
   - Example: `+` (addition), `-` (subtraction), `*` (multiplication), `/` (division), `%` (modulus).  
   - Example Output:  
     ```c
     int sum = 5 + 3;
     printf("%d", sum);
     ```
     **Output**:  
     ```
     8
     ```

2. **Relational Operators**  
   - Used to compare two values.  
   - Example: `==` (equal to), `!=` (not equal to), `>` (greater than), `<` (less than).  
   - Example Output:  
     ```c
     int result = (5 > 3);
     printf("%d", result);
     ```
     **Output**:  
     ```
     1  // 1 means true, 0 means false
     ```

3. **Logical Operators**  
   - Used to combine conditions.  
   - Example: `&&` (AND), `||` (OR), `!` (NOT).  
   - Example Output:  
     ```c
     int logic = (5 > 3) && (2 < 4);
     printf("%d", logic);
     ```
     **Output**:  
     ```
     1  // Both conditions are true, so the result is 1 (true)
     ```

---

### **Input/Output Functions**

1. **printf()**  
   - Displays output to the screen.  
   - Example:  
     ```c
     int sum = 10;
     printf("Sum is %d", sum);
     ```
     **Output**:  
     ```
     Sum is 10
     ```

2. **scanf()**  
   - Takes input from the user.  
   - Example:  
     ```c
     int num;
     printf("Enter a number: ");
     scanf("%d", &num);
     printf("You entered: %d", num);
     ```
     **Input**: `5`  
     **Output**:  
     ```
     Enter a number: 5
     You entered: 5
     ```

---

### **Control Structures**

1. **if-else**  
   - Executes different blocks of code based on conditions.  
   - Example:  
     ```c
     int x = 7;
     if (x > 0) {
         printf("Positive");
     } else {
         printf("Negative");
     }
     ```
     **Output**:  
     ```
     Positive
     ```

2. **Loops**  
   - **for loop**: Repeats a block of code a specific number of times.  
     Example:  
     ```c
     for (int i = 0; i < 3; i++) {
         printf("%d ", i);
     }
     ```
     **Output**:  
     ```
     0 1 2
     ```

   - **while loop**: Repeats a block of code as long as a condition is true.  
     Example:  
     ```c
     int x = 3;
     while (x > 0) {
         printf("%d ", x);
         x--;
     }
     ```
     **Output**:  
     ```
     3 2 1
     ```

---

### **Constants**

- **Constant Declaration**: Variables whose value cannot be changed.  
  - Example:  
    ```c
    const int MAX = 100;
    printf("%d", MAX);
    ```
    **Output**:  
    ```
    100
    ```

- **#define**: Preprocessor directive used to define constants.  
  - Example:  
    ```c
    #define PI 3.14
    printf("%f", PI);
    ```
    **Output**:  
    ```
    3.140000
    ```

---

### **Example Program**

```c
#include <stdio.h>

int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);

    if (num % 2 == 0) {
        printf("Even");
    } else {
        printf("Odd");
    }

    return 0;
}
```

**Input**: `4`  
**Output**:  
```
Enter a number: 4
Even
```

---
