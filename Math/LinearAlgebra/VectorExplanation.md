
# 🧭 Finding Direction Cosines: A to B Using the Feynman Technique

Let’s use the **Feynman Technique** to deeply understand how to find the **direction cosines** of a vector that goes from point **A(1, 2, -3)** to point **B(-1, -2, 1)**.

---

## 🧠 Step 1: Understand What You’re Solving

We want the **direction cosines** of a vector from **A to B**.

Direction cosines are simply the **cosines of the angles** that a vector makes with the **x, y, and z axes**. They are important because they **describe the direction of the vector** in 3D space, independent of its length.

---

## ✏️ Step 2: Find the Vector from A to B

To find the vector **-> $\( \vec{AB} \)$ .**, subtract coordinates of A from B:

$$
\[
\vec{AB} = \vec{B} - \vec{A} = (-1, -2, 1) - (1, 2, -3)
\]
$$

$$
\[
\vec{AB} = (-1 - 1, -2 - 2, 1 - (-3)) = (-2, -4, 4)
\]
$$

So the vector is:

$$
\[
\vec{AB} = \langle -2, -4, 4 \rangle
\]
$$

---

## 📏 Step 3: Find the Magnitude (Length) of the Vector

Use the 3D distance formula:

$$
\[
|\vec{AB}| = \sqrt{(-2)^2 + (-4)^2 + (4)^2} = \sqrt{4 + 16 + 16} = \sqrt{36} = 6
\]
$$

---

## 📐 Step 4: Divide Each Component by the Magnitude

This gives you the **unit vector** in the same direction. These values are the **direction cosines**:

$$
\[
\cos(\alpha) = \frac{-2}{6} = -\frac{1}{3}
\]
$$

$$
\[
\cos(\beta) = \frac{-4}{6} = -\frac{2}{3}
\]
$$

$$
\[
\cos(\gamma) = \frac{4}{6} = \frac{2}{3}
\]
$$

---

## ✅ Final Answer: Direction Cosines

$$
\[
(\cos \alpha, \cos \beta, \cos \gamma) = \left( -\frac{1}{3}, -\frac{2}{3}, \frac{2}{3} \right)
\]
$$

---

## 🧠 Recap via Feynman Technique

1. **What are we doing?**  
   We’re finding the **angles** between a vector and each axis — using cosines.

2. **How do we do it?**  
   - Get the vector components by subtracting point A from B.
   - Compute its **length**.
   - Divide each component by the length to get the **cosines** of the direction angles.

3. **Why does this work?**  
   The **unit vector** points in the same direction as the original vector and has a length of 1. Its components are exactly the cosines of the angles it makes with the x, y, and z axes.

---

## References

- [Direction Cosines – Wikipedia](https://en.wikipedia.org/wiki/Direction_cosine)
- [Feynman Technique – Wikipedia](https://en.wikipedia.org/wiki/Feynman_Technique)
