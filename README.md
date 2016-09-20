# SuperLU_w64_mkl

This project is reminder for compiling SuperLU in Windows and linking it with Intel MKL.

### SuperLU

SuperLU contains a set of subroutines to solve a sparse linear system 
A*X=B. It uses Gaussian elimination with partial pivoting (GEPP). 
The columns of A may be preordered before factorization; the 
preordering for sparsity is completely separate from the factorization.

SuperLU is implemented in ANSI C, and must be compiled with standard 
ANSI C compilers. It provides functionality for both real and complex
matrices, in both single and double precision.

Official Homepage: http://crd.lbl.gov/~xiaoye/SuperLU/
