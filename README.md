# Linear Algebra Library in Python

A collection of linear algebra algorithms implemented from scratch in Python without using external numerical libraries such as NumPy.

## Project Overview

This project explores the implementation of fundamental linear algebra concepts and numerical algorithms through pure Python code. The repository includes custom implementations of vector and matrix operations, matrix decompositions, linear system solvers, basis transformations, determinant computation, eigenvalue methods, and singular value decomposition.

The goal of the project was to understand the mathematical foundations behind commonly used numerical linear algebra techniques by implementing them directly.

## Implemented Topics

### Core Data Structures

* Complex Number Class
* Vector Class
* Matrix Class

### Matrix Operations

* Matrix Addition
* Matrix Multiplication
* Transpose
* Conjugate
* Conjugate Transpose

### Matrix Analysis

* Rank
* Nullity
* Reduced Row Echelon Form (RREF)
* Matrix Property Checks

### Linear Systems

* Gaussian Elimination
* Consistency Checking
* Solution Set Computation

### Matrix Decompositions

* LU Decomposition
* PLU Decomposition
* QR Factorization
* Cholesky Decomposition
* Polar Decomposition
* Singular Value Decomposition (SVD)

### Eigenvalue Methods

* Characteristic Polynomial
* Eigenvalues and Eigenvectors
* Matrix Diagonalization

### Coordinate Transformations

* Basis Computation
* Change of Basis
* Coordinate Representations

## Technical Highlights

* Implemented entirely in Python
* No use of NumPy or external numerical libraries
* Object-oriented implementations of vectors, matrices, and complex numbers
* Focus on understanding and implementing algorithms from first principles

## Repository Structure

The project is organized according to the original problem specification, with each directory corresponding to a major topic in linear algebra.

### q1 – Core Data Structures and Matrix Operations

* q1a: Complex Number class with arithmetic operations
* q1b: Vector class implementation
* q1c: Matrix class implementation
* q1d: Matrix construction from vectors
* q1e: Matrix addition and multiplication
* q1f: Row and column extraction operations
* q1g: Transpose, conjugate, and conjugate-transpose operations

### q2 – Matrix Property Verification

Functions for determining important matrix properties, including:

* Zero matrix
* Symmetric matrix
* Hermitian matrix
* Square matrix
* Orthogonal matrix
* Unitary matrix
* Scalar matrix
* Singular and invertible matrices
* Identity matrix
* Nilpotent matrix
* Diagonalizability
* Positive definiteness
* LU decomposability

### q3 – Elementary Matrix Operations

* Vector length and matrix size
* Rank and nullity computation
* Reduced Row Echelon Form (RREF)
* Linear independence testing
* Basis and dimension computation
* Rank factorization
* LU and PLU decompositions

### q4 – Systems of Linear Equations

* Linear system representation
* Consistency checking
* Gaussian elimination
* Subspace verification
* Solution set computation
* PLU-based system solving

### q5 – Matrix Inverses

* Inverse via row reduction
* Inverse via adjoint method

### q6 – Coordinates and Change of Basis

* Membership in a span
* Linear combination representation
* Span comparison
* Coordinate computation
* Change of basis matrices
* Coordinate transformation between bases

### q7 – Determinants

* Cofactor expansion method
* PLU-based determinant computation
* Determinant computation using elementary row operations

### q8 – Inner Products and Orthogonalization

* Inner products
* Orthogonality testing
* Gram-Schmidt orthogonalization
* QR factorization
* Moore-Penrose pseudoinverse
* Least-squares solutions

### q9 – Eigenvalues and Eigenvectors

* Polynomial root finding (Aberth method)
* Characteristic polynomial computation
* Minimal polynomial computation
* Eigenvalue computation
* Matrix similarity testing
* Algebraic and geometric multiplicities
* Eigenbases
* Matrix diagonalization

### q10 – Advanced Matrix Decompositions

* Polar decomposition
* Cholesky decomposition
* Singular Value Decomposition (SVD)

