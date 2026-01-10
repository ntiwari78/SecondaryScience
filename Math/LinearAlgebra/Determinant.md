- https://ncert.nic.in/textbook/pdf/lemh104.pdf

---

![det](https://github.com/ntiwari78/SecondaryScience/blob/main/Math/LinearAlgebra/Determinants.png)



# 📘 Briefing on the Theory and Application of Determinants

> *"All Mathematical truths are relative and conditional."*
> — **C.P. Steinmetz**

---

## 🧾 Executive Summary

This document offers a comprehensive overview of **determinants**, a key concept in [linear algebra](https://en.wikipedia.org/wiki/Linear_algebra). A **determinant** is a scalar value uniquely associated with any square matrix, used to assess whether a system of linear equations has a unique solution.

* A **non-zero determinant** of the coefficient matrix implies a **unique solution**.
* Calculating determinants depends on matrix size:

  * **1×1**: Simple scalar
  * **2×2** and **3×3**: Use **minors** and **cofactors**
* Determinants are foundational in computing the **adjoint** and **inverse** of matrices.
* Applications include solving systems of equations and computing geometric properties like the **area of a triangle**.

---

## 1. The Concept of a Determinant

### 1.1 Definition and Notation

Let **A = [aᵢⱼ]** be a square matrix of order *n*. The determinant is a scalar function:

```math
f: M → K, f(A) = k
```

* Notations: `det(A)`, `|A|`, or `∆`
* **Only defined for square matrices**

### 1.2 Link to Systems of Linear Equations

For a system:

```
a₁x + b₁y = c₁  
a₂x + b₂y = c₂
```

The determinant:

```
|A| = a₁b₂ – a₂b₁
```

Determines if a **unique solution** exists (`|A| ≠ 0`).

---

## 2. Calculation of Determinants

### 2.1 Order 1 Matrix

```latex
A = [a]
|A| = a
```

### 2.2 Order 2 Matrix

```latex
A = [[a₁₁, a₁₂], [a₂₁, a₂₂]]
|A| = a₁₁a₂₂ – a₁₂a₂₁
```

**Example:**

```
|2, 4; -1, 2| = (2)(2) – (4)(–1) = 8
```

### 2.3 Order 3 Matrix

```latex
|A| = a₁₁(a₂₂a₃₃ – a₂₃a₃₂) – a₁₂(a₂₁a₃₃ – a₂₃a₃₁) + a₁₃(a₂₁a₃₂ – a₂₂a₃₁)
```

Or using minors and signs:

```latex
|A| = (–1)¹⁺¹ a₁₁ M₁₁ + (–1)¹⁺² a₁₂ M₁₂ + (–1)¹⁺³ a₁₃ M₁₃
```

**Tips:**

* Expand along a row/column with **most zeros**
* If **A = kB**, then `|A| = kⁿ|B|` (for order *n* matrices)

---

## 3. Minors and Cofactors

### 3.1 Definitions

* **Minor (Mᵢⱼ)**: Determinant of sub-matrix formed by deleting i-th row and j-th column
* **Cofactor (Aᵢⱼ)**: `Aᵢⱼ = (–1)ⁱ⁺ʲ * Mᵢⱼ`

### 3.2 Determinant Using Cofactors

```latex
|A| = a₁₁A₁₁ + a₁₂A₁₂ + a₁₃A₁₃
```

### 3.3 Zero-Sum Property

When cofactors of a different row are used:

```latex
a₁₁A₂₁ + a₁₂A₂₂ + a₁₃A₂₃ = 0
```

---

## 4. Adjoint and Inverse of a Matrix

### 4.1 Adjoint

```latex
adj(A) = transpose of cofactor matrix of A
```

### 4.2 Singular vs. Non-Singular

* **Singular**: `|A| = 0`
* **Non-singular**: `|A| ≠ 0`

### 4.3 Key Theorems

1. **Matrix Identity:**

```latex
A * adj(A) = |A| * I
```

2. **Product Rule:**

```latex
|AB| = |A| * |B|
```

3. **Adjoint Determinant:**

```latex
|adj A| = |A|ⁿ⁻¹
```

4. **Invertibility:**

```latex
A⁻¹ exists iff |A| ≠ 0
```

### 4.4 Inverse Formula

```latex
A⁻¹ = (1 / |A|) * adj(A)
```

---

## 5. Applications

### 5.1 Area of a Triangle

Given vertices (x₁, y₁), (x₂, y₂), (x₃, y₃):

```math
Area = (1/2) * | x₁(y₂ - y₃) + x₂(y₃ - y₁) + x₃(y₁ - y₂) |
```

Or determinant form:

```latex
Area = (1/2) * |det([[x₁, y₁, 1], [x₂, y₂, 1], [x₃, y₃, 1]])|
```

**Remarks:**

* Use **absolute value**
* Area is **zero** if points are **collinear**

### 5.2 Solving Systems of Linear Equations

Matrix form:

```latex
AX = B
```

* A: coefficient matrix
* X: variables column
* B: constants column

Check consistency using determinants:

| Case               | Condition              | Result |       |                |    |   |
| ------------------ | ---------------------- | ------ | ----- | -------------- | -- | - |
| Unique solution    | `                      | A      | ≠ 0`  | Use `X = A⁻¹B` |    |   |
| No solution        | Depends on `           | A      | `and` | [A             | B] | ` |
| Infinite solutions | Special dependent form |        |       |                |    |   |

---

## 6. Historical Context

* **Ancient China**: Elimination with rods
* **Seki Kowa** (Japan, 1683): Early formal use of determinants
* **Vandermonde** (1771): Defined determinants as independent functions
* **Laplace** (1772): Expansion using minors
* **Lagrange** & **Gauss**: Applied in broader math contexts
* **Binet & Cauchy** (1812): Product of matrices theorem
* **Jacobi**: Popularized and formalized modern determinant theory

---

## 🔗 References

* [Determinant – Wikipedia](https://en.wikipedia.org/wiki/Determinant)
* [Matrix (mathematics) – Wikipedia](https://en.wikipedia.org/wiki/Matrix_%28mathematics%29)
* [Inverse Matrix – MathWorld](https://mathworld.wolfram.com/MatrixInverse.html)
* [Minors and Cofactors – MathWorld](https://mathworld.wolfram.com/Minor.html)
* [Area of a Triangle Using Determinants](https://www.cuemath.com/geometry/area-of-a-triangle-using-determinants/)
* [Linear Equation System – Wikipedia](https://en.wikipedia.org/wiki/System_of_linear_equations)
* [Cofactor Matrix – Wikipedia](https://en.wikipedia.org/wiki/Adjugate_matrix)



# 📘 Study Guide: An Introduction to Determinants

---

## 📝 Short-Answer Quiz

Answer the following questions in **2–3 sentences** based on the source material.

1. What is a determinant, and what kind of matrix is it associated with?
2. Explain the process for calculating the determinant of a 2×2 matrix.
3. Describe the relationship between a system of linear equations and the determinant of its coefficient matrix.
4. How is the formula for the area of a triangle expressed using a determinant? What does it mean if the resulting area is zero?
5. What is the key difference between the minor and the cofactor of an element in a matrix?
6. How is the value of a 3×3 determinant calculated using the method of expansion along its first row?
7. Define the adjoint of a square matrix. How is it constructed?
8. What is the difference between a singular and a non-singular matrix? Which type of matrix is invertible?
9. Explain the "Matrix Method" for solving a system of linear equations represented as AX = B.
10. If a system of equations AX = B has a singular coefficient matrix A, what conditions determine if the system is inconsistent?

---

## ✅ Answer Key

1. A **determinant** is a unique number (real or complex) associated with a **square matrix**. It acts as a function mapping square matrices to scalar values.

2. For a 2×2 matrix `A = [[a₁₁, a₁₂], [a₂₁, a₂₂]]`, the determinant is calculated as:

   ```
   det(A) = a₁₁a₂₂ – a₁₂a₂₁
   ```

3. The determinant of a system's **coefficient matrix** determines whether the system has a **unique solution**. If the determinant is non-zero, the system is solvable with a unique solution.

4. The **area** of a triangle with vertices (x₁, y₁), (x₂, y₂), (x₃, y₃) is given by:

   ```
   Δ = ½ * |x₁(y₂ – y₃) + x₂(y₃ – y₁) + x₃(y₁ – y₂)|
   ```

   If the result is zero, the points are **collinear**.

5. A **minor** is the determinant of the sub-matrix after removing one row and column. The **cofactor** is the signed minor: `Aᵢⱼ = (–1)ⁱ⁺ʲ * Mᵢⱼ`.

6. A 3×3 determinant is calculated by **expanding along a row** (typically the first):

   ```
   |A| = a₁₁A₁₁ – a₁₂A₁₂ + a₁₃A₁₃
   ```

   Each term is an element multiplied by its cofactor (a 2×2 determinant).

7. The **adjoint** of a square matrix A is the **transpose** of its cofactor matrix. It's built by calculating all cofactors, forming a matrix, and transposing it.

8. A matrix is **singular** if `|A| = 0` and **non-singular** if `|A| ≠ 0`. Only **non-singular matrices** are invertible.

9. The **Matrix Method** solves `AX = B` by multiplying both sides by `A⁻¹` (if it exists):

   ```
   X = A⁻¹B
   ```

10. If `A` is singular (`|A| = 0`) and `(adj A)B ≠ O`, then the system is **inconsistent** and has **no solution**.

---

## 🧠 Essay Questions

Answer in paragraph form using detailed explanations.

1. **Determinants and Linear Systems:**
   Discuss how the value of the determinant of a coefficient matrix A in `AX = B` determines whether the system has a unique, no, or infinite number of solutions. Include the role of singular and non-singular matrices.

2. **Finding the Inverse of a 3×3 Matrix:**
   Describe the steps: define **minors** and **cofactors**, build the **adjoint**, and apply the inverse formula

   ```
   A⁻¹ = (1 / |A|) * adj(A)
   ```

   Explain why `|A|` must be non-zero.

3. **3×3 Determinant by Expansion:**
   Explain how to expand along a row or column, why the result is the same regardless of choice, and tips for simplifying (e.g., choose rows with zeros).

4. **Minors, Cofactors, and Inverse Theorem:**
   Link the concepts of **minors**, **cofactors**, **adjoint**, and the theorem:

   ```
   A * adj(A) = |A| * I
   ```

   Show how this leads to the formula for the inverse of a matrix.

5. **Applications of Determinants:**
   Explain how determinants are used to:

   * Calculate the **area of a triangle**
   * Solve a **system of linear equations**
     Discuss the geometric and algebraic significance.

---

## 📚 Glossary of Key Terms

| **Term**                | **Definition**                                                                             |   |                           |
| ----------------------- | ------------------------------------------------------------------------------------------ | - | ------------------------- |
| **Adjoint of a matrix** | The transpose of the matrix of cofactors of A, denoted `adj A`.                            |   |                           |
| **Cofactor**            | `Aᵢⱼ = (–1)ⁱ⁺ʲ * Mᵢⱼ`, the signed minor of element `aᵢⱼ`.                                  |   |                           |
| **Consistent system**   | A system of equations that has at least one solution.                                      |   |                           |
| **Determinant**         | A scalar value associated with a square matrix, denoted `                                  | A | `or`det(A)`.              |
| **Inconsistent system** | A system of equations that has no solution.                                                |   |                           |
| **Invertible matrix**   | A square matrix `A` such that `A⁻¹` exists and `AA⁻¹ = I`.                                 |   |                           |
| **Matrix Method**       | Solving `AX = B` by finding `X = A⁻¹B`.                                                    |   |                           |
| **Minor**               | The determinant of a sub-matrix formed by deleting one row and one column.                 |   |                           |
| **Non-singular matrix** | A square matrix with `                                                                     | A | ≠ 0`; **invertible**.     |
| **Singular matrix**     | A square matrix with `                                                                     | A | = 0`; **non-invertible**. |
| **Square matrix**       | A matrix with the same number of rows and columns. Only square matrices have determinants. |   |                           |

---

## 🔗 References

* [Determinant – Wikipedia](https://en.wikipedia.org/wiki/Determinant)
* [Matrix Inverse – Wolfram MathWorld](https://mathworld.wolfram.com/MatrixInverse.html)
* [Systems of Linear Equations – Wikipedia](https://en.wikipedia.org/wiki/System_of_linear_equations)
* [Minors and Cofactors – MathWorld](https://mathworld.wolfram.com/Minor.html)
* [Area of a Triangle Using Determinants](https://www.cuemath.com/geometry/area-of-a-triangle-using-determinants/)
* [Jacobi and History of Determinants](https://en.wikipedia.org/wiki/Determinant#History)

