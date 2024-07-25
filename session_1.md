## Pseudocode for linear algebra
```pyhton
FUNCTION matrix_sum(A,B);
   get the no of rows and columns in matrix A
   create an empty matrix C with same dimension
   FOR  each row i;
       FOR each column j;
           set C[i][j] to the sum of A[i][j] and B[i][j]
   return the matrix C
END FUNCTION



## Pseudo code for solution of system of equations

FUNCTION solution(a,b);
   create augmented matrix: K=[a|b]
   reduce in row reduced echelon form
   rank = no. of non zero rows of row reduced echelon form
   if rank(k)!= rank(a):
     print("system is consistent")
   else if:
     solve using back substitution
END FUNCTION
```python





