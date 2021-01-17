Computational Fluid Dynamics (CFD) schemes implemented in FORTRAN using Finite-Volume and Finite-Difference Methods

Fortran 95 is a higher level language than C. It is much easier and safer to work with single and especially multidimensional arrays in Fortran 95 than C or even C++. There are two compilers, g95 and gfortran, under the GNU license that are freely available for Linux, Windows, and Mac.

Matlab is very popular with engineers. One can think of Fortran as a compiled Matlab, admittedly without the built-in graphics. No matter what higher level programming toolkit you're using-MATLAB, NumPy, LAPACK,pretty much all matrix subroutines are ultimately compiling down to BLAS and thereby running in Fortran. Fortran is still the fastest language for doing such work, and since speed is of such import for numerical analysis (CFD & CHT), it's worth it to dispatch that code to Fortran
