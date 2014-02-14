This is an implementation in C++ of the Rabin-Miller primality test. It supports arbitrary precision arithmetic and performs well for extremely large numbers. Note that the parameter LMAX needs to be set so that it can process large enough numbers. LMAX = 200 is useful for numbers with ~300 digits and LMAX = 500 is more than enough for numbers with ~1000 digits.
It needs C++11 to compile and it takes as input (from stdin) a number T, and then a list of T numbers to be tested. The code is completely modularized so it can be used as an auxiliary function on other code.

If you have any questions regarding this implementation or the algorithm feel free to contact me at martinarjovsky@gmail.com
