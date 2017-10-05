This python library contains some useful functions to deal with
prime numbers and whole numbers. 

The file primelib.py or primliby.pyc will simply import by the import-statement.
Important primelib.py or primelib.pyc must been in your project directory.

Example: (In your project)

import primelib

print primelib.isPrime(13)   // will print out 'True'
print primelib.primeFactorization(40)  // will print out [2,2,2,5]

OR 

from primelib import *

print isPrime(...) 

More information about the functions.

help(function_name)

For example:

help(isPrime)

---------------------------

Overview about functions:

-------------------------

isPrime (number)

input: positive integer 'number'
returns true if 'number' is prime otherwise false.

-------------------------

sieveEr (N)

input: positive integer 'N' > 2
returns a list of prime numbers from 2 up to N.
        
This function implements the algorithm called
sieve of erathostenes. 

---------------------------

getPrimeNumbers (N)

input: positive integer 'N' > 2
returns a list of prime numbers from 2 up to N (inclusive)
This function is more efficient as function sieveEr(...)


----------------------------

primeFactorization (number)

input: integer 'number' > 1
returns a list of the prime number factors of 'number'

-------------------------------

greatestPrimeFactor (number)

input: integer 'number' > 1
returns the greatest prime number factor of 'number'

---------------------------------

smallestPrimeFactor (number)

input: integer 'number' > 1
returns the smallest prime number factor of 'number'

----------------------------------

isEven (number)

input: integer 'number'
returns true if 'number' is even, otherwise false.

-----------------------------------

isOdd (number)

input: integer 'number'
returns true if 'number' is odd, otherwise false.

------------------------------------

ggT (number1, number2)

Greatest common divisor

input: two positive integer 'number1' and 'number2'
returns the greatest common divisor of 'number1' and 'number2'

-------------------------------------

kgV (number1, number2)

Least common multiple

input: two positive integer 'number1' and 'number2'
returns the least common multiple of 'number1' and 'number2'

---------------------------------------

goldbach(number)

Goldbach's assumption

input: a even positive integer 'number' > 2
returns a list of two prime numbers whose sum is equal to 'number'
