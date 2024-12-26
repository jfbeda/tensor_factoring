# tensor_factoring

This repository (github.com/jfbeda/tensor_factoring) includes a single file (main.nb) containing a couple of useful functions for the manipulations of tensors and tensor products in Mathematica, associated with a chapter from [[Insert name of textbook]] where the functions are used to solve a couple of basic problems.

Included in the file are the functions:

# rankDecompositionOrderTwoToMatricesRREF

This computes a rank decomposition of an n-by-m matrix M such that M = D1^T D2 for matrices D1 and D2 that are r-by-n and r-by-m with r =  rank(M) by using an algorithm (algorithm 1 in the book) that makes use of the RREF (reduced row echelon form) of M.

# rankDecompositionOrderTwoToMatricesSVD

This computes a rank decomposition of an n-by-m matrix M such that M = D1^T D2 for matrices D1 and D2 that are r-by-n and r-by-m with r =  rank(M) by using an algorithm (algorithm 1 in the book) that makes use of the SVD (singular value decomposition) of M.

# displayRankDecompositionOrderTwo

This computes a rank decomposition of an n-by-m matrix M and displays it in the form M = sum over of tensor products of rank 1 tensors. This usines rankDecompositionOrderTwoToMatricesRREF to do the backend, but could be switched easily to use rankDecompositionOrderTwoToMatricesSVD instead.

# and a few hard-coded tensors (u,v,Z)

These can all be accessed simply by calling their respective names, and are used in the chapter.
