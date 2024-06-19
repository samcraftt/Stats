# Stats

This C program generates a series of random numbers and
computes basic statistics on those numbers. The stats program takes exactly 4 command line arguments: the
number of sample runs to make, the size of the population (# of random values) for each
sample, the lower bound for each random number, and the upper bound for each random
number. Every argument must be an integer, the number of samples and population size must
be positive, and the upper bound must be at least as large as the lower bound.
The program generates a set of random numbers (equal to the population size) for each
sample run. For each set of random numbers, the program prints the sample number, the
minimum value in the set, the maximum value in the set, the mean of the set, and the
population standard deviation of the set.
