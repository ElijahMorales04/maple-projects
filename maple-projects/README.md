# 📘 Symbolic Computation in Mathematics (Maple) – COP4313

> **Student:** Elijah Morales  
> **University:** University of South Florida  
> **Course Code:** COP4313-001  
> **Term:** Fall 2024  

---

## 🧠 Summary

In *Symbolic Computation in Mathematics*, I developed recursive and symbolic algorithms using **Maple** for advanced mathematical modeling. Projects involved:

- 🔐 **RSA decryption**
- 🔁 **Lucas numbers and Josephus problem**
- 🧮 **Eigenvalue & determinant verification**
- 📊 **Orthogonal polynomial generation (Legendre Pₙ)**
- 🧩 **Discrete algebraic systems & polynomial identities**

These implementations reinforced my expertise in performance optimization, symbolic computation, mathematical logic, and numerical verification using a high-level computational system.

---

## 📁 Repository Structure

```plaintext
maple/
├── assignment1.mws
├── assignment2.mws
├── assignment5.mws
├── assignment6.mws
├── test1.mws
├── test2.mws
├── test3.mws
└── README.md
📂 Assignments Overview
📝 Assignment 1
Numerical integration using int and evalf

Expression analysis and Maple syntax differences (:=, =, /, \)

Polynomial factorization and root solving

📝 Assignment 2
Programmatic summation and filtering

Custom ISPRIME procedure

Discovery of 2-pseudoprimes and factorization routines

📝 Assignment 5
Eigenvalue vs determinant verification via RandomMatrix, Eigenvalues, and Determinant

Constructed special matrices Aₙ(i, j) using conditional logic

Verified eigenvalues, eigenspaces, and symbolic characteristics

📝 Assignment 6
Recursive Josephus(n) procedure

Variadic DeleteMinMaxAvg with argument parsing

Efficient recursive matrix and polynomial power calculators MatPow and PolyPow

📊 Exams
🧪 Test 1
Defined a function in 3 ways (arrow, unapply, proc)

Verified multi-representation sums of squares

Classified primes by modulo and tested digit statistics

Proved expressions are perfect squares symbolically

🧪 Test 2
Lucas number algorithms: iterative vs recursive (with memoization)

Determinants, characteristic polynomials, and eigen-analysis

Polynomial identity verification using solve and allvalues

Graphical plotting and animation of tangents using plots[animate]

🧪 Test 3
Polynomial matching by symbolic coefficient comparison

Matrix orthogonality verification and singularity investigation

Closed-form recurrence solving via rsolve

Legendre polynomial generation via generating functions & orthogonality testing

Full RSA decryption using modular exponentiation and base conversion

🔧 Key Maple Skills
rsolve, solve, evalf, expand, simplify, int, diff, factor

Matrix, Determinant, Eigenvalues, CharacteristicPolynomial

PowerMod, MatrixInverse, proc, args, sort

orthopoly[P], plots, animate, cat, convert, flatten

Recursive optimization with option remember

✅ How to Run
Open .mws files in Maple 2019 or later.

Execute entire worksheet or selected code blocks (Shift+Enter).

For visualizations and animation, ensure plots package is loaded.

📌 Notes
This repo is intended as a showcase of symbolic computation techniques in Maple and mathematical insight development. Projects reflect real-world applications in cryptography, linear algebra, and functional programming.