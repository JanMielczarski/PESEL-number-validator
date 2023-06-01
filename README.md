# PESEL-number-validator
Simple Python project checking the validity of PESEL number.
PESEL has 11 digits, where the last is a checksum. This code calculates validity of PESEL, using following expression:
A*1 + B*3 + C*7 + D*9 + E*1 + F*3 + G*7 + H*9 + I*1 + J*3 
Where ABCDEFGHIJ are first 10 digits of the number.
