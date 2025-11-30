# Sparse Matrix Addition in C (3-Tuple Representation)

This program performs **addition of two sparse matrices** using their **3-tuple (row, column, value)** representation.

It:
- Accepts two sparse matrices from the user
- Converts each matrix into a 3-tuple (tuple) form
- Adds the two sparse matrices (if dimensions match)
- Displays:
  - Original matrices  
  - Tuple representation of A and B  
  - Tuple representation of the sum  
  - Final summed matrix in normal 2D form  

---

## 🧮 What is a Sparse Matrix?

A sparse matrix is a matrix where most of the elements are **zero**.  
Instead of storing all elements, we store only the **non-zero** elements as:
```text
row_index  column_index  value
