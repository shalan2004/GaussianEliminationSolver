# **LinearSolver**  
A Python GUI application for solving systems of linear equations using **Gaussian Elimination**. This project features an intuitive **Tkinter** interface and provides step-by-step visualization of the solution process.  

2nd Year - Linear Algebra course


## **Features**  
- **Step-by-step Gaussian Elimination**: View each transformation of the augmented matrix.  
- **Interactive Tkinter GUI**: User-friendly interface for inputting equations and constants.  
- Handles cases with:  
  - **Unique solutions**.  
  - **Infinite solutions**.  
  - **No solution**.  
- Displays the augmented matrix transformation at every step.  

## **How the Program Works**  

### **1. Input**  
- Enter the **number of rows** (equations) and **columns** (variables).  
- Provide the coefficients and constants for the equations in a single text box:  
  - Each row corresponds to one equation.  
  - Separate the coefficients of variables with spaces, and include the constant at the end of the row.  
- **Example Input**:
```
2 1 -1 8 -3 -1 2 -11
```
- **This represents the system of equations**:
```
2x + y - z = 8  
-3x - y + 2z = -1
```

### **2. Process**  
- The program applies **Gaussian Elimination** to solve the system of equations.  
- It performs row operations to convert the augmented matrix to **row echelon form**.  

### **3. Output**  
- The program displays:  
1. **Step-by-step transformations** of the augmented matrix.  
2. The final matrix in **row echelon form**.  
3. The solution to the system, if it exists, in the format:  
   ```
   x1 = value1, x2 = value2, ..., xn = valueN
   ```
- If there are **infinite solutions** or **no solution**, the program explicitly states it.

