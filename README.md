# expm_block_tri
EXPM_BLOCK_TRI - Exponential of block triangular matrix.

 [Fa,Fb,L] = expm_block_tri(A,B,E) computes Fa = e^A, Fb = e^B, and
 L = D_{exp}(A,B,E), the (1,2) block of exp([A E;O B]), without explicitly
 computing the exponential of the block triangular matrix, exp([A E;O B]).

   References:
   A. H. Al-Mohy, Generalizing the Fr\'echet Derivative Algorithm for 
       the Matrix Exponential, Submitted.

   A. H. Al-Mohy and N. J. Higham, Computing the Fr\'echet Derivative of 
      the Matrix Exponential, with an Application to Condition Number 
      Estimation, SIAM J. Matrix Anal. Appl., 30(4), (2009), pp. 1639-1657.

   A. H. Al-Mohy and N. J. Higham, A new scaling and squaring algorithm
      for the matrix exponential, SIAM J. Matrix Anal. Appl., 31(3),
      (2009), pp. 970-989.

  Note: qtri_struct used by expm, a MATLAB internal function,
  ...\toolbox\matlab\matfun\private\qtri_struct
