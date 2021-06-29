# Factorial-Trailing-Zeros
The number of zeros trailing in the factorial of any given natural number.


##	Theorem

Let $f(n)$ give the number of trailing zeros in the base ten representation of $n!$. Then,

$f(n) = \sum_{i=1}^{k} [\frac{n}{5^i}]$

where $ k = [log_5^n]$ .


## How to run

Clone repository

`git clone https://github.com/hritikvalluvar/Factorial-Trailing-Zeros` 

Change current directory

`cd Factorial-Trailing-Zeros`

Compile main.cpp

`g++ main.cpp`

Run output file

`./a.out`