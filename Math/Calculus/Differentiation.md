
# Differentiation and Derivatives

**Differentiation** is a mathematical tool used to calculate small changes in a quantity with respect to another quantity.

The result of this process is called the **derivative**.

## Standard Notation

The standard notation for the derivative of a function, representing the change in $\( y \)$ with respect to $\( x \)$ , is:

$$
\[
\frac{dy}{dx}
\]
$$

## Applications: Instantaneous Rates of Change

Differentiation is commonly used to express **instantaneous rates of change**. Examples include:

- **Velocity** $(\( V \))$ : Defined as the change in position $(\( x \))$ with respect to time $(\( t \))$ .

$$
  \[
  V = \frac{\Delta x}{\Delta t} \approx \frac{dx}{dt}
  \]
$$

- **Acceleration** $(\( a \))$ : Defined as the change in velocity $(\( V \))$ with respect to time $(\( t \))$ .

$$
  \[
  a = \frac{\Delta V}{\Delta t} \approx \frac{dV}{dt}
  \]
$$

- **General Rate of Change**:

$$
  \[
  \frac{dm}{dt}
  \]
$$

  This represents the change in $\( m \)$ with respect to time $\( t \)$.

## References

- [Differentiation (Wikipedia)](https://en.wikipedia.org/wiki/Differentiation)
- [Derivative (Wikipedia)](https://en.wikipedia.org/wiki/Derivative)
- [Velocity (Wikipedia)](https://en.wikipedia.org/wiki/Velocity)
- [Acceleration (Wikipedia)](https://en.wikipedia.org/wiki/Acceleration)


---
---



# Fundamental Differentiation Rules

This section outlines key rules used in [differentiation](https://en.wikipedia.org/wiki/Differentiation), the process of computing derivatives. Each rule includes examples demonstrating its application.

---

## 1. Power Rule

Used to differentiate expressions of the form $\( x^n \)$:

$$
\[
\frac{d(x^n)}{dx} = nx^{n-1}
\]
$$

**Examples:**

- $\( \frac{d(x^5)}{dx} = 5x^4 \)$
- $\( \frac{d(y^3)}{dy} = 3y^2 \)$
- $\( \frac{d(x^{-3})}{dx} = -3x^{-4} \)$
- $\( \frac{d(x)}{dx} = 1 \)$
- $\( \frac{d(m^{3/2})}{dm} = \frac{3}{2}m^{1/2} = \frac{3}{2}\sqrt{m} \)$

---

## 2. Constant Rule

The derivative of a constant is always zero:

$$
\[
\frac{d(\text{constant})}{dx} = 0
\]
$$

**Examples:**

- $\( \frac{d(3)}{dx} = 0 \)$
- $\( \frac{d(101)}{dy} = 0 \)$
- $\( \frac{d(-131)}{dm} = 0 \)$
- $\( \frac{d(\sin 60^\circ)}{dx} = 0 \)$

---

## 3. Constant Multiple Rule

A constant multiplied by a function remains outside the derivative operation:

$$
\[
\frac{d(c \cdot x^n)}{dx} = c \cdot \frac{d(x^n)}{dx}
\]
$$

**Examples:**

- $\( \frac{d(3x^2)}{dx} = 3 \cdot 2x = 6x \)$
- $\( \frac{d(5x^{-2})}{dx} = 5 \cdot (-2x^{-3}) = -10x^{-3} \)$

---

## 4. Sum and Difference Rule

The derivative of a sum/difference equals the sum/difference of individual derivatives:

$$
\[
\frac{d(m \pm n)}{dx} = \frac{dm}{dx} \pm \frac{dn}{dx}
\]
$$

**Example:**

- $\( \frac{d(x^3 + x)}{dx} = 3x^2 + 1 \)$

---

## 5. Product Rule

Used when differentiating the product of two functions:

$$
\[
\frac{d(m \cdot n)}{dx} = \frac{dm}{dx} \cdot n + \frac{dn}{dx} \cdot m
\]
$$

**Example:**

- $\( \frac{d(x^2 \sin x)}{dx} = (2x)\sin x + x^2 \cos x \)$

---

## 6. Quotient Rule

Used when differentiating the quotient of two functions:

$$
\[
\frac{d\left(\frac{m}{n}\right)}{dx} = \frac{\frac{dm}{dx} \cdot n - \frac{dn}{dx} \cdot m}{n^2}
\]
$$

**Examples:**

- $\( \frac{d\left(\frac{x^2}{\sin x}\right)}{dx} = \frac{2x \cdot \sin x - x^2 \cdot \cos x}{\sin^2 x} \)$
- $\( \frac{d\left(\frac{\cos x}{x^5}\right)}{dx} = \frac{-\sin x \cdot x^5 - 5x^4 \cdot \cos x}{x^{10}} \)$

---

## 7. Trigonometric Derivatives

These are specific rules for basic [trigonometric functions](https://en.wikipedia.org/wiki/Trigonometric_functions):

$$
\[
\frac{d(\sin x)}{dx} = \cos x
\]
$$

$$
\[
\frac{d(\cos x)}{dx} = -\sin x
\]
$$

---

## References

- [Differentiation (Wikipedia)](https://en.wikipedia.org/wiki/Differentiation)
- [Derivative (Wikipedia)](https://en.wikipedia.org/wiki/Derivative)
- [Power Rule (Khan Academy)](https://www.khanacademy.org/math/ap-calculus-ab/ab-differentiation-1-new/ab-1-4/a/power-rule)
- [Product Rule (Wikipedia)](https://en.wikipedia.org/wiki/Product_rule)
- [Quotient Rule (Wikipedia)](https://en.wikipedia.org/wiki/Quotient_rule)
- [Trigonometric Functions (Wikipedia)](https://en.wikipedia.org/wiki/Trigonometric_functions)


---
---


# Product Rule (Rule 5)

The **Product Rule** is one of the core rules in [differentiation](https://en.wikipedia.org/wiki/Differentiation), used when finding the derivative of the product of two functions.

---

## Formula

If $\( m(x) \)$ and $\( n(x) \)$ are two differentiable functions, the derivative of their product is given by:

$$
\[
\frac{d(m \cdot n)}{dx} = \left(\frac{dm}{dx}\right)n + \left(\frac{dn}{dx}\right)m
\]
$$

In simpler terms:

> Take the derivative of the first function, multiply by the second function, then add the derivative of the second function multiplied by the first function.

---

## Example 1: $\( \frac{d(x^2 \sin x)}{dx} \)$

Let:
- $\( m = x^2 \)$
- $\( n = \sin x \)$

**Step-by-step:**

1. Apply the Product Rule:

$$
   \[
   \frac{d(x^2 \sin x)}{dx} = \frac{d(x^2)}{dx} \cdot \sin x + \frac{d(\sin x)}{dx} \cdot x^2
   \]
$$

3. Compute individual derivatives:
   - $\( \frac{d(x^2)}{dx} = 2x \)$
   - $\( \frac{d(\sin x)}{dx} = \cos x \)$

4. Substitute:

$$   
   \[
   2x \cdot \sin x + x^2 \cdot \cos x
   \]
$$

**Final Result:**

$$
\[
\boxed{2x \sin x + x^2 \cos x}
\]
$$

---

## Example 2: $\( \frac{d(y^4 \cos y)}{dy} \)$

Let:

- $\( m = y^4 \)$
- $\( n = \cos y \)$

**Step-by-step:**

1. Apply the Product Rule:

$$
   \[
   \frac{d(y^4 \cos y)}{dy} = \frac{d(y^4)}{dy} \cdot \cos y + \frac{d(\cos y)}{dy} \cdot y^4
   \]
$$

2. Compute individual derivatives:
   - $\( \frac{d(y^4)}{dy} = 4y^3 \)$
   - $\( \frac{d(\cos y)}{dy} = -\sin y \)$

3. Substitute:

$$   
   \[
   4y^3 \cdot \cos y + (-\sin y) \cdot y^4
   \]
$$

**Final Result:**

$$
\[
\boxed{4y^3 \cos y - y^4 \sin y}
\]
$$

---

## References

- [Product Rule (Wikipedia)](https://en.wikipedia.org/wiki/Product_rule)
- [Trigonometric Derivatives (Khan Academy)](https://www.khanacademy.org/math/ap-calculus-ab/ab-differentiation-2-new/ab-2-5/a/differentiating-trig-functions-review)
- [Derivative (Wikipedia)](https://en.wikipedia.org/wiki/Derivative)

---
---

# Quotient Rule (Dividend Rule – Rule 6)

The **Quotient Rule**, also known as the **Dividend Rule**, is used in [differentiation](https://en.wikipedia.org/wiki/Differentiation) to find the derivative of a function expressed as the **quotient of two functions**.

---

## Formula

For a function $\( \frac{m(x)}{n(x)} \)$ , where both $\( m \)$ and $\( n \)$ are differentiable functions of $\( x \)$ , the derivative is:

$$
\[
\frac{d\left(\frac{m}{n}\right)}{dx} = \frac{\frac{dm}{dx} \cdot n - \frac{dn}{dx} \cdot m}{n^2}
\]
$$

This means:

1. Differentiate the **numerator**, multiply by the **denominator**.
2. Subtract the product of the **derivative of the denominator** and the **numerator**.
3. Divide the entire result by the **square of the denominator**.

---

## Example 1: $\( \frac{d}{dx} \left( \frac{x^2}{\sin x} \right) \)$

Let:
- $\( m = x^2 \)$
- $\( n = \sin x \)$

**Step-by-step:**

1. Apply the Quotient Rule:

$$
   \[
   \frac{d}{dx} \left( \frac{x^2}{\sin x} \right) = \frac{\frac{d(x^2)}{dx} \cdot \sin x - \frac{d(\sin x)}{dx} \cdot x^2}{\sin^2 x}
   \]
$$

2. Compute derivatives:
   - $\( \frac{d(x^2)}{dx} = 2x \)$
   - $\( \frac{d(\sin x)}{dx} = \cos x \)$

3. Substitute:

$$
   \[
   \frac{2x \cdot \sin x - x^2 \cdot \cos x}{\sin^2 x}
   \]
$$

**Final Result:**

$$
\[
\boxed{\frac{2x \sin x - x^2 \cos x}{\sin^2 x}}
\]
$$

---

## Example 2: $\( \frac{d}{dx} \left( \frac{\cos x}{x^5} \right) \)$

Let:
- $\( m = \cos x \)$
- $\( n = x^5 \)$

**Step-by-step:**

1. Apply the Quotient Rule:

$$
   \[
   \frac{d}{dx} \left( \frac{\cos x}{x^5} \right) = \frac{\frac{d(\cos x)}{dx} \cdot x^5 - \frac{d(x^5)}{dx} \cdot \cos x}{(x^5)^2}
   \]
$$

1. Compute derivatives:
   - $\( \frac{d(\cos x)}{dx} = -\sin x \)$
   - $\( \frac{d(x^5)}{dx} = 5x^4 \)$

2. Substitute:

$$
   \[
   \frac{-\sin x \cdot x^5 - 5x^4 \cdot \cos x}{x^{10}}
   \]
$$


**Final Result:**

$$
\[
\boxed{\frac{-\sin x \cdot x^5 - 5x^4 \cdot \cos x}{x^{10}}}
\]
$$

---

## References

- [Quotient Rule (Wikipedia)](https://en.wikipedia.org/wiki/Quotient_rule)
- [Derivative (Wikipedia)](https://en.wikipedia.org/wiki/Derivative)
- [Trigonometric Derivatives (Khan Academy)](https://www.khanacademy.org/math/ap-calculus-ab/ab-differentiation-2-new/ab-2-5/a/differentiating-trig-functions-review)

---
---

# Summary of Differentiation Rules

1. **Power Rule**:  

$$
   \[
   \frac{d(x^n)}{dx} = nx^{n-1}
   \]
$$

2. **Constant Rule**:  

$$
   \[
   \frac{d(\text{constant})}{dx} = 0
   \]
$$

3. **Constant Multiple Rule**:  

$$
   \[
   \frac{d(c \cdot f(x))}{dx} = c \cdot \frac{df(x)}{dx}
   \]
$$

4. **Sum and Difference Rule**:  

$$
   \[
   \frac{d(m \pm n)}{dx} = \frac{dm}{dx} \pm \frac{dn}{dx}
   \]
$$

5. **Product Rule**:  

$$
   \[
   \frac{d(m \cdot n)}{dx} = \left(\frac{dm}{dx}\right)n + \left(\frac{dn}{dx}\right)m
   \]
$$

6. **Quotient Rule (Dividend Rule)**:
 
$$  
   \[
   \frac{d\left(\frac{m}{n}\right)}{dx} = \frac{\frac{dm}{dx} \cdot n - \frac{dn}{dx} \cdot m}{n^2}
   \]
$$

---

## 7. Chain Rule

The **Chain Rule** is used to differentiate **composite functions** — functions of the form $\( y = f(g(x)) \)$ , where one function is nested inside another.

### Chain Rule Formula

If $\( y = f(g(x)) \)$ , then:

$$
\[
\frac{dy}{dx} = \frac{df}{dg} \cdot \frac{dg}{dx}
\]
$$

Or more commonly written as:

$$
\[
\frac{d}{dx}f(g(x)) = f'(g(x)) \cdot g'(x)
\]
$$

---

### Example: $\( \frac{d}{dx} \left( \sin(x^2) \right) \)$

Here, the outer function is $\( f(u) = \sin u \)$ , and the inner function is $\( g(x) = x^2 \)$ .

1. Differentiate the outer function with respect to the inner function:

$$
   \[
   \frac{d}{du}(\sin u) = \cos u
   \]
$$

2. Multiply by the derivative of the inner function:

$$
   \[
   \frac{d}{dx}(x^2) = 2x
   \]
$$

3. Apply the chain rule:

$$
   \[
   \frac{d}{dx}(\sin(x^2)) = \cos(x^2) \cdot 2x
   \]
$$

**Final Result:**

$$
\[
\boxed{\frac{d}{dx}(\sin(x^2)) = 2x \cos(x^2)}
\]
$$

---

## References

- [Chain Rule (Wikipedia)](https://en.wikipedia.org/wiki/Chain_rule)
- [Derivative (Wikipedia)](https://en.wikipedia.org/wiki/Derivative)
- [Trigonometric Derivatives (Khan Academy)](https://www.khanacademy.org/math/ap-calculus-ab/ab-differentiation-2-new/ab-2-5/a/differentiating-trig-functions-review)
