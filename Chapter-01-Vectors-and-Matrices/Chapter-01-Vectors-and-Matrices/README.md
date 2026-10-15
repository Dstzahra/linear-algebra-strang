# 📐 Chapter 1: Preface & Section 1.1 — Vectors and Linear Combinations

Welcome to the conceptual notes for Gilbert Strang's *Introduction to Linear Algebra* (6th Edition).

---

## 📌 Core Concept: What is a Vector?

A vector can be represented in two complementary ways:
1. **Algebraic View:** An ordered list of numbers (column vector).
2. **Geometric View:** An arrow in space starting from the origin $(0,0,0)$ with a specific direction and length.

### Example Vectors from Preface
We start with two vectors in 3D space ($\mathbb{R}^3$):

$$a_1 = \begin{bmatrix} 2 \\ 3 \\ 1 \end{bmatrix}, \quad a_2 = \begin{bmatrix} 1 \\ 4 \\ 2 \end{bmatrix}, \quad \mathbf{0} = \begin{bmatrix} 0 \\ 0 \\ 0 \end{bmatrix}$$

---

## 💡 Linear Combinations: $c a_1 + d a_2$

The fundamental operation in linear algebra is taking **linear combinations** of vectors.

### 1. Vector Addition ($a_1 + a_2$)
$$a_1 + a_2 = \begin{bmatrix} 2 \\ 3 \\ 1 \end{bmatrix} + \begin{bmatrix} 1 \\ 4 \\ 2 \end{bmatrix} = \begin{bmatrix} 3 \\ 7 \\ 3 \end{bmatrix}$$

### 2. Scalar Multiplication ($2a_1$)
$$2a_1 = 2 \begin{bmatrix} 2 \\ 3 \\ 1 \end{bmatrix} = \begin{bmatrix} 4 \\ 6 \\ 2 \end{bmatrix}$$

### 3. Combining Operations ($2a_1 + a_2$)
$$2a_1 + a_2 = \begin{bmatrix} 4 \\ 6 \\ 2 \end{bmatrix} + \begin{bmatrix} 1 \\ 4 \\ 2 \end{bmatrix} = \begin{bmatrix} 5 \\ 10 \\ 4 \end{bmatrix}$$

---

## 🎨 Geometric Visualizations

### 2D Projection (Book Diagram)
Drawing 3D vectors on a 2D page:
* $a_1$ and $a_2$ define a flat plane.
* All linear combinations $c a_1 + d a_2$ fill that entire plane.

### 3D Spatial Representation
In 3D coordinate space $(x, y, z)$:
* Vector $a_1$ reaches the point $(2, 3, 1)$.
* Vector $a_2$ reaches the point $(1, 4, 2)$.
* The combination $2a_1 + a_2$ reaches the point $(5, 10, 4)$.
