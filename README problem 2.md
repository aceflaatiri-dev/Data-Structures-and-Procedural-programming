project: dot product and orthogonality check

description:
-------------
this project includes a procedure and a function to calculate the dot (scalar) product of two vectors in real space.
it also checks if the given pairs of vectors are orthogonal (i.e., their dot product is zero).

features:
---------
1. procedure version (using pass-by-reference):
   - calculates the dot product and stores it in a variable.
   - checks orthogonality by comparing the result to zero.

2. function version (using pass-by-value):
   - returns the dot product directly.
   - same orthogonality check using returned result.

input:
------
- the number of vector pairs (n)
- the size of each vector
- the values of each vector for every pair

output:
-------
- displays whether each pair of vectors is orthogonal or not
- also shows the intermediate dot product values if needed

structure:
----------
- dot_product: a procedure or function to compute the scalar product.
- check_orthogonality: main algorithm using the procedure version.
- check_orthogonality_func: main algorithm using the function version.

notes:
------
- all code is written in lowercase for readability and human feel.
- arrays are used to store vector values.
- nested loops are used for input and computation.

example:
--------
input:
  size of vectors: 3
  v1: [1, 2, -1]
  v2: [2, -1, 0]

output:
  vectors 1 are not orthogonal

to test:
--------
- copy the code to any pseudocode editor or language that supports arrays and procedures/functions.
- follow the input prompts and verify the output.
