

- **Definition**: A set or series of instructions to carry out a task or solve a problem, transforming input into the required output.
- **Purpose**: To produce the required output from the given input in an orderly, clear, and structured manner.
- **Types**:
  - **Sequential**: Steps are performed in a strict sequence.
  - **Selection**: A condition determines which of several paths will be followed.
  - **Repetition**: A set of instructions is repeated until a condition is met.

---

### **Tools for Developing Algorithms**

1. **Flowchart**  
   - **Definition**: A graphical representation of an algorithm using different shapes to represent processes, inputs, outputs, and decisions.
   - **Symbols**:
     - **Oval (Start/Stop)**: Represents the beginning and end of a process.
     - **Parallelogram (Input/Output)**: Used for inputs and outputs.
     - **Rectangle (Processing)**: Represents operations or processes.
     - **Diamond (Decision)**: Used for conditions where a true/false decision is made.
     - **Arrow (Flow Line)**: Indicates the flow of the process.

2. **Pseudocode**  
   - **Definition**: A text-based representation of an algorithm, using simple English-like statements and symbols.
   - **Key Characteristics**:
     - Uses common symbols for arithmetic (`+`, `-`, `*`, `/`).
     - Keywords like `READ`, `PRINT`, `IF`, `ELSE` are commonly used.
     - Organized and indented for readability.

---

### **Examples of Algorithms**

1. **Sequential Algorithm Example**  
   **Task**: Print the sum of two numbers.  
   
   **Pseudocode**:
   
   ```plaintext
   ALGORITHM sum
   A -> 0, B -> 0, SUM -> 0
   INPUT A, B
   SUM -> A + B
   OUTPUT SUM
   END sum
   ```
   

2. **Selection Algorithm Example**  
   **Task**: Determine if a number is positive or negative.  
   
   **Pseudocode**:
   
   ```plaintext
   ALGORITHM pos_neg
   N -> 0
   INPUT N
   IF N < 0 THEN
      OUTPUT "NEGATIVE"
   ELSE IF N == 0 THEN
      OUTPUT "INVALID"
   ELSE
      OUTPUT "POSITIVE"
   END IF
   END pos_neg
   ```

3. **Repetition Algorithm Example**  
   **Task**: Print numbers from 1 to 10.  
   
   **Pseudocode**:
   
   ```plaintext
   ALGORITHM display_from_1_to_10
   N -> 1
   WHILE N <= 10
      OUTPUT N
      N -> N + 1
   END WHILE
   END display_from_1_to_10
   ```
 
 
### **Key Notes on Algorithm Development**

- **Sequential structure**: Executes steps one after the other.
- **Selection structure**: Uses conditions to determine which path to follow.
- **Repetition structure**: Repeats steps until a certain condition is met.

---
