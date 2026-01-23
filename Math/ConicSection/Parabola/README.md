# Briefing on the Parabola: Focus and Directrix

## Executive Summary

This document synthesizes a comprehensive analysis of the **parabola**, beginning with its fundamental geometric definition and culminating in a practical method for identifying its key components from a standard algebraic equation.

A **parabola** is geometrically defined as the locus of all points in a plane that are equidistant from a fixed point, known as the **[focus](https://en.wikipedia.org/wiki/Focus_(geometry))**, and a fixed line, known as the **[directrix](https://en.wikipedia.org/wiki/Directrix)**.

### Core Findings

1. **From Geometry to Algebra**  
   By applying the [distance formula](https://en.wikipedia.org/wiki/Distance) to the definition of a parabola, it is mathematically proven that this locus of points forms the familiar U-shape. The resulting general equation for a parabola with focus \((a, b)\) and directrix \(y = k\) is:

   $\[
   y - \frac{b + k}{2} = \frac{1}{2(b - k)}(x - a)^2
   \]$

2. **From Algebra to Geometry**  
   Reversing this process, a standard parabolic equation in the form:

   $\[
   y - y_1 = A(x - x_1)^2
   \]$

   can be analyzed to determine the focus and directrix:

   - **Vertex**: $\((x_1, y_1)\)$
   - **Focus**: $\((x_1, y_1 + \frac{1}{4A})\)$
   - **Directrix**: 4\(y = y_1 - \frac{1}{4A}\)$

This provides an intuitive bridge between geometric and algebraic representations of parabolas that open upward or downward.

---

## 1. The Geometric Foundation of a Parabola

### Core Components

- **Focus**: Fixed point $\((a, b)\)$
- **Directrix**: Fixed line $\(y = k\)$
- **Locus of Points**: Set of all points $\((x, y)\)$ equidistant from the focus and directrix

> "We want to find all of the points in the xy-plane that are equidistant to this focus and this directrix."

### Derivation of the Parabolic Equation

1. **Set Up the Equidistance Condition**  
   $\[
   \text{Distance to Focus} = \text{Distance to Directrix}
   \]$

2. **Apply Distance Formulas**  
   - To Focus: $\(\sqrt{(x - a)^2 + (y - b)^2}\)$  
   - To Directrix: $\(|y - k|\)$

3. **Equate and Simplify**  
   $\[
   (x - a)^2 + (y - b)^2 = (y - k)^2
   \]$

4. **Expand and Cancel Terms**  
   $\[
   (x - a)^2 + y^2 - 2yb + b^2 = y^2 - 2yk + k^2
   \]$

5. **Isolate and Factor**  
   Simplify the equation to express it in terms of $\((x - a)^2\) and \(y\)$

### Resulting General Equation

$\[
y - \frac{b + k}{2} = \frac{1}{2(b - k)}(x - a)^2
\]$

This links the geometric definition to its algebraic form.

---

## 2. Determining the Focus and Directrix from a Standard Equation

### Case Study: $\(y = x^2\)$

1. **Standardize**:  
   $\[
   y - 0 = 1(x - 0)^2
   \]$

2. **Pattern Match**:
   - $\(a = 0\)$
   - $\(\frac{b + k}{2} = 0\) → \(b + k = 0\)$
   - $\(\frac{1}{2(b - k)} = 1\) → \(b - k = \frac{1}{2}\)$

3. **Solve**:
   - $\(b = \frac{1}{4}\)$
   - $\(k = -\frac{1}{4}\)$

4. **Conclusion**:
   - Vertex: $\((0, 0)\)$
   - Focus: $\((0, \frac{1}{4})\)$
   - Directrix: $\(y = -\frac{1}{4}\)$

### General Formulas for Any Parabola

Given:  
$\[
y - y_1 = A(x - x_1)^2
\]$

| Component        | Derivation / Relationship               | General Formula                  |
|------------------|------------------------------------------|----------------------------------|
| Vertex           | Makes both sides zero                    | $\((x_1, y_1)\)$                   |
| Focus (x-coord)  | Same as vertex x                         | $\(x_1\)4                          |
| Coefficient (A)  | $\(A = \frac{1}{2(b - k)}\)$               | —                                |
| Vertex y-coord   | $\(y_1 = \frac{b + k}{2}\)$                | —                                |
| Focus y-coord    | From solving the system                  | $\(b = y_1 + \frac{1}{4A}\)$       |
| Directrix        | From solving the system                  | $\(k = y_1 - \frac{1}{4A}\)$       |

---

## 3. Practical Application and Intuitive Understanding

### The $\(\frac{1}{4A}\)$ Distance Rule

For any parabola in standard form $\(y - y_1 = A(x - x_1)^2\)$ :

- The **focus** and **directrix** are each $\(|\frac{1}{4A}|\)$ away from the vertex.
- The **focus** lies *inside* the parabola (above vertex for $\(A > 0\))$ .
- The **directrix** lies *outside* the parabola (below vertex for $\(A > 0\))$ .

### Example: $\(y - 1 = 2(x - 3)^2\)$

1. **Vertex**: $\((3, 1)\)$  
2. **A = 2**  
3. **-> $\(\frac{1}{4A} = \frac{1}{8}\)$  ->**

- **Focus**:  
  $\(y = 1 + \frac{1}{8} = \frac{9}{8}\)$  
  → $\((3, \frac{9}{8})\)$

- **Directrix**:  
  $\(y = 1 - \frac{1}{8} = \frac{7}{8}\)$  
  → $\(y = \frac{7}{8}\)$

This demonstrates how the standard form enables direct calculation of the parabola's focus and directrix.

---

## References

- [Parabola – Wikipedia](https://en.wikipedia.org/wiki/Parabola)
- [Focus (Geometry) – Wikipedia](https://en.wikipedia.org/wiki/Focus_(geometry))
- [Directrix – Wikipedia](https://en.wikipedia.org/wiki/Directrix)
- [Distance Formula – Wikipedia](https://en.wikipedia.org/wiki/Distance)
