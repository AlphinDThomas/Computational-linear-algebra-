## Pseudocode for linear algebra
```pyhton
FUNCTION matrix_sum(A,B);
   get the no of rows and columns in matrix A
   create an empty matrix C with same dimension
   FOR  each row i;
       FOR each column j;
           set C[i][j] to the sum of A[i][j] and B[i][j]
   return the matrix c
END FUNCTION

