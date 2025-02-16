# **Gaussian Elimination Solver**

A Python-based graphical application designed to solve systems of linear equations using **Gaussian Elimination**. Featuring an intuitive **Tkinter** interface, this project offers a step-by-step visualization of the solution process to enhance understanding of linear algebra concepts.

## **Course Context**
Developed as part of the **2nd Year - Linear Algebra Course**, this tool helps students grasp the mechanics of Gaussian Elimination by providing an interactive learning experience.

## **Features**
- **Step-by-step Gaussian Elimination:** Observe each transformation in the augmented matrix.
- **User-friendly Tkinter GUI:** Easily input equations and constants.
- **Supports multiple solution cases:**
  - Unique solutions.
  - Infinite solutions.
  - No solution.
- **Real-time visualization:** Displays matrix transformations at every step.

## **How It Works**
### **Input**
- Specify the **number of equations (rows)** and **variables (columns)**.
- Enter the coefficients and constants as space-separated values in a text box.
- **Example Input:**
2 1 -1 8 -3 -1 2 -11

This corresponds to the system:
2x + y - z = 8
-3x - y + 2z = -1

### **Processing**
- The program applies **Gaussian Elimination** to manipulate the augmented matrix.
- Row operations systematically reduce the matrix to **row echelon form**.

### **Output**
- The program presents:
1. **Sequential transformations** of the augmented matrix.
2. The final matrix in **row echelon form**.
3. The computed solution in the format:
   ```
   x1 = value1, x2 = value2, ..., xn = valueN
   ```
4. Clear messages for **infinite solutions** or **no solution** cases.
