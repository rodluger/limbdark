7/11/2018

Comparison with Pal's code, ntiq-fortran.f, is accomplished
as follows:

1).  Compile code from the prompt with:

tests$ gfortran -O3 -ffixed-line-length-none ntiq-fortran.f -o ntiq-fortran

2).  Run the program:

tests$ ./ntiq-fortran > ntiq_test.out

3).  Plot the results:

julia> include("compare_pal.jl")

