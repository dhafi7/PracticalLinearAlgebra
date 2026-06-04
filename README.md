# 📐 Practical Linear Algebra for Data Science (Python Implementations)

This repository contains a collection of highly comprehensive, structurally rigorous Jupyter Notebooks (`.ipynb`) replicating the complete curriculum, algebraic foundations, and hands-on code examples from the book *Practical Linear Algebra for Data Science: From Core Concepts to Applications* by Mike X Cohen.

The primary objective of this material is to bridge the gap between abstract mathematical proofs and applied data science operations—transforming theoretical linear algebra concepts into executable, vectorized Python operations.

---

## 📂 Repository Structure

The code and concepts are organized into chronological chapters, forming a progressive engineering track from raw scalar computations to high-dimensional matrix factorizations:

* **`Chapter_1_Introduction.ipynb`**
  An overview of linear algebra's role in the data science landscape. Establishes the computational framework of the series, introducing the execution environments of NumPy, SciPy, and Matplotlib.
* **`Chapter_2_Vectors.ipynb`**
  The foundational building blocks of linear algebra. Covers vector representations, geometry, algebraic operations, scalar multiplication, the dot product, vector lengths (norms), and unit vectors.
* **`Chapter_3_Vector_Spaces.ipynb`**
  Exploring vector geometry and spatial structures. Covers linear combinations, vector spans, linear dependence vs. independence, vector subspaces, basis sets, and coordinate systems.
* **`Chapter_4_Matrices.ipynb`**
  An introduction to the geometry and algebra of 2D data arrays. Covers matrix types (diagonal, symmetric, identity, orthogonal), scalar-matrix math, matrix-vector multiplication, and matrix-matrix multiplication paradigms.
* **`Chapter_5_Matrix_Operations.ipynb`**
  Advanced algebraic operations for structural manipulation. Details the matrix transpose, trace, rank, determinants, and the mathematical mechanics of calculating the structural information of a transformation tensor.
* **`Chapter_6_Matrix_Inversion.ipynb`**
  Solving system equations and understanding mathematical division for matrices. Covers the definition of inversion, the identity matrix bridge, Singular vs. Non-singular states, and computing the Moore-Penrose Pseudoinverse for overdetermined systems.
* **`Chapter_7_Orthogonality.ipynb`**
  Orthogonal matrices, projections, and decompositions. Explores perpendicular vector geometry, dot-product zero states, projection spaces, and the complete Gram-Schmidt Orthogonalization workflow.
* **`Chapter_8_Least_Squares.ipynb`**
  The mathematical backbone of regression analysis. Applies projections and pseudoinverses to solve unsolvable, overdetermined linear systems ($Ax = b$), minimizing the sum of squared errors for predictive modeling.
* **`Chapter_9_Eigendecomposition.ipynb`**
  Unlocking internal matrix invariants. Details eigenvalues ($\lambda$) and eigenvectors ($v$), characteristic polynomials, diagonalizing square matrices, and the foundational mechanics of Principal Component Analysis (`PCA`).
* **`Chapter_10_Singular_Value_Decomposition.ipynb`**
  The pinnacle of matrix factorization. Breaks down any rectangular matrix into three distinct component spaces ($A = U\Sigma V^T$), enabling Low-Rank Matrix Approximations, image compression, and latent semantic analysis.

---

## 🛠️ Tech Stack & Numerical Ecosystem

The programmatic applications throughout these modules bypass raw loops in favor of optimized, vectorized routines within the standard Python scientific stack:
* **`NumPy`** — The industry-standard library for managing multi-dimensional `ndarray` coordinate tensors and vectorized algebraic equations.
* **`SciPy`** — Advanced linear algebra operations, including specialized solver routines and sparse matrix factorizations (`scipy.linalg`).
* **`Matplotlib` & `Seaborn`** — 2D and 3D visualization utilities used to map vector geometry, grid transformations, eigenvectors, and projection space planes.

---

## 🚀 How to Execute These Modules

Every notebook file is stored in a clean, fully compliant JSON structural layout. To explore the visual transformations and mathematical mechanics:
1. Clone this repository onto your local computation environment.
2. Launch your preferred development pipeline interface (**Google Colab**, **JupyterLab**, or via the native Jupyter Notebook extension in **VS Code**).
3. Execute the code blocks sequentially to witness how linear transformations warp coordinate space vectors and extract structural data.
