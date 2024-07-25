## Pseudocode
```python
FUNCTION matrix_sum(A, B):
    Get the number of rows and columns in matrix A
    Create an empty matrix C with the same dimensions
    FOR each row i:
        FOR each column j:
            Set C[i][j] to the sum of A[i][j] and B[i][j]
    RETURN the matrix C
END FUNCTION
```
$$A=\begin{pmatrix}
1&2&3 \\
4&5&6 \\
7&8&9 \\
\end{pmatrix} $$

## Psuedocode _ Solution of System of Equations
```python
FUNCTION Solution(A,b):
    Create augmented matrix:K=[A/b]
    Reduce in Row Reduced Echelon Form
    Rank = no. of non zero rows of RREF
    IF Rank(K)!=Rank(A):
        print("System is inconsistent")
    ELSE IF:
        Solve using back substitution
END FUNCTION
```
