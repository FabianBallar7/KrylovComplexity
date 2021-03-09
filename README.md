# KrylovComplexity
Krylox Complexity calculation for MBL systems


This code was developed to calculate the Lanczos algorithm in the operator Hilbert space. 

We are concerned with Pauli Strings which are tensor products of pauli matrices. We encode these as array where X->1, Y->2, Z->3 & I->0. So that for instance, a Pauli X_1 Z_2 Y_3 I_4 would be identified with the array [1,3,2,0]. For large system size this maybe to annoying to carry so we hash this to a sparse array by means of the base 4 transformation. 
