# LUP-Decomposition
- The basic principle used to write the LU decomposition algorithm and flowchart is – ““A square matrix [A] can be written as the product of a lower triangular matrix [L] and an upper triangular matrix [U], one of them being unit triangular, if all the principal minors of [A] are non-singular.”
- So, for a linear system AX = b, the given matrix [A] can be decomposed into the product two lower and upper triangular matrices.
## Algorithm
- Start
- Read the elements of augmented matrix into arrays a and b
- Calculate elements of L and U
- Print elements of L and U
- Find V by solving LV = B by forward substitution
- Find X by solving UX = V by backward substitution
- Print Array X as the solution
- Stop

## Steps to run program on google colab
- `%%writefile filename.c`[This will be written at the start of the program]
- For compiling follow this instruction<br>
    `%%shell `<br>
`gcc filename.c -o output`<br>
`./output`
