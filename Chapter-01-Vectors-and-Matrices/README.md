# 📐 Chapter 1: Vectors and Matrices

Welcome to the **Chapter 1** module for *Introduction to Linear Algebra* (6th Edition) by Gilbert Strang.

---

## 📌 Chapter Overview

In this chapter, we explore the fundamental building blocks of linear algebra: **vectors**, **linear combinations**, **dot products**, and **matrices**.

| Section | Topic | Key Concepts |
| :--- | :--- | :--- |
| **1.1** | Vectors and Linear Combinations | Column vectors, Vector addition, Scalar multiplication |
| **1.2** | Lengths and Angles from Dot Products | Dot product $v \cdot w$, Vector norm $\Vert{}v\Vert{}$, Cosine formula |
| **1.3** | Matrices and Their Column Spaces | Matrix-vector multiplication $Ax$, Column space |
| **1.4** | Matrix Multiplication $AB$ and $CR$ | Matrix product rules, Factorization $A = CR$ |

---

## 💡 Core Mathematical Concepts

### 1. Vector Addition & Scalar Multiplication
Given two vectors $v, w \in \mathbb{R}^n$ and scalars $c, d \in \mathbb{R}$:

$$c v + d w = c \begin{bmatrix} v_1 \\ v_2 \end{bmatrix} + d \begin{bmatrix} w_1 \\ w_2 \end{bmatrix} = \begin{bmatrix} c v_1 + d w_1 \\ c v_2 + d w_2 \end{bmatrix}$$

### 2. Dot Product and Orthogonality
The inner product (dot product) of two vectors measures their geometric relationship:

$$v \cdot w = v_1 w_1 + v_2 w_2 + \dots + v_n w_n$$

* **Length (Norm):** $\Vert{}v\Vert{} = \sqrt{v \cdot v}$
* **Angle ($\theta$):** $\cos\theta = \frac{v \cdot w}{\Vert{}v\Vert{} \Vert{}w\Vert{}}$
* **Orthogonality:** Vectors are perpendicular if $v \cdot w = 0$.

---

## 💻 Code & Exercises

Check out the interactive Python implementations and visualizations in our Jupyter Notebook:
* 📓 [`code_and_exercises.ipynb`](./code_and_exercises.ipynb)
