# Lab: 6.0.4

**Objective:**

- Understand the concept and importance of Two-Dimensional Arrays in Java development.
- Learn how to implement Two-Dimensional Arrays using Java's array syntax.
- Explore practical applications of Two-Dimensional Arrays in real-world Java projects.
- Identify common pitfalls and best practices when working with Two-Dimensional Arrays.
- Gain hands-on experience with a complete Java example that demonstrates Two-Dimensional Arrays.

**Prerequisites:**

- Solid understanding of Java programming basics.
- Familiarity with one-dimensional arrays in Java.
- Basic knowledge of nested loops and control structures.

**What You'll Achieve:**

- Develop a solid understanding of Two-Dimensional Arrays in Java.
- Implement practical examples that can be applied in real-world scenarios.
- Enhance your skills in matrix operations and data manipulation.

**Assignment Details**

In the main method of the `MatrixOperations` class, implement the following operations:

1. Create two 3x3 matrices (matrix1 and matrix2) with random integers between 1 and 100.
2. Print both matrices in a formatted manner.
3. Add the matrices and print the result.
4. Multiply the matrices and print the result.
5. Find and print the transpose of the first matrix.
6. Find and print the maximum value in each matrix.

**Example Output**

```
Matrix 1:
23  45  12
67  89  34
56  78  90

Matrix 2:
11  22  33
44  55  66
77  88  99

Sum of matrices:
34  67  45
111 144 100
133 166 189

Product of matrices:
3190  4785  6380
7723 11585 15447
10912 16368 21824

Transpose of Matrix 1:
23  67  56
45  89  78
12  34  90

Maximum value in Matrix 1: 90
Maximum value in Matrix 2: 99
```

**Starter Code**

The `MatrixOperations.java` file contains the following starter code:

```java
package academy.javapro.lab;

import java.util.Random;

public class MatrixOperations {
    public static void main(String[] args) {
        Random random = new Random();

        // TODO: Create two 3x3 matrices with random values

        // TODO: Print both matrices

        // TODO: Add matrices

        // TODO: Multiply matrices

        // TODO: Find transpose of first matrix

        // TODO: Find maximum value in each matrix
    }
}

```

**Hints**

- Use nested loops to iterate through 2D arrays.
- For creating matrices with random values: `int value = random.nextInt(100) + 1`;
- When adding matrices, add corresponding elements: `result[i][j] = matrix1[i][j] + matrix2[i][j];`
- For matrix multiplication, remember the rule: `result[i][j] += matrix1[i][k] * matrix2[k][j];`
- When transposing a matrix, swap rows and columns: `transpose[j][i] = matrix[i][j];`
- Use a variable initialized to `Integer.MIN_VALUE` to find the maximum value.
- Use `System.out.printf("%-4d", value)` for formatted printing of matrix elements.

**Submission Instructions**

1. Fork the repository
2. Clone your fork
3. Navigate into the repository
4. Implement the required operations in the `main` method of `MatrixOperations.java`
5. Test your implementation with various inputs
6. Git add, commit, and push to your fork
7. Submit a pull request
    - Set the title of the pull request to your first name and last name
    - In the comment, briefly explain your implementation approach and any challenges you faced

Remember, the goal is to learn and have fun! Don't hesitate to ask for help if you get stuck.