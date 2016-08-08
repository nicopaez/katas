Kata ISBN-10
============

ISBN-10 is made up of 9 digits plus a check digit (which may be 'X'). Spaces and hyphens may be included in a code, but are not significant. This means that 9780471486480 is equivalent to 978-0-471-48648-0 and 978 0 471 48648 0.

The check digit for ISBN-10 is calculated by multiplying each digit by its position (i.e., 1 x 1st digit, 2 x 2nd digit, etc.), summing these products together and taking modulo 11 of the result (with 'X' being used if the result is 10).

Valid examples: 0471958697, 0 471 95869 7, 0-471-95869-7, 155404295X
Invalid examples: 
* 0471958697 (wrong verifier)
* 0471958 (wrong length)
* a471958697 (wrong digit)

Write logic to validate if a given string is a valid ISBN-10.