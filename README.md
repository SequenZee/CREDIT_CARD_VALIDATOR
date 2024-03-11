# CREDIT CARD VALIDATOR 💳

---

## Overview
This program implements the Luhn Algorithm to validate credit card numbers entered by the user. The Luhn Algorithm, also known as the mod-10 algorithm, is a checksum formula used to validate various identification numbers, including credit card numbers.

## Implementation
- The program consists of a main function and a helper function.
- The helper function, `isNumberString`, checks whether a given string contains only numerical characters.
- The main function prompts the user to enter a credit card number.
- It then performs the following steps as per the Luhn Algorithm:
  1. Doubles every second digit from the right, starting from the second-to-last digit, and adds the digits together if the result is a two-digit number.
  2. Adds the remaining digits (not doubled) from the credit card number.
  3. Checks if the sum is a multiple of 10.
- Finally, it outputs whether the entered credit card number is valid or invalid.

---

---

## Usage
1. Create a file named 'credit.cpp'
2. Compile your code:
```
clang++ credit.cpp
```
3. Run your code:
```
./a.out
```
4. Enter a credit card number when prompted.
5. The program will determine if the entered credit card number is valid or not.
6. To exit the program, type 'exit' when prompted for a credit card number.

---

## Sample Input/Output
```
This program uses the Luhn Algorithm to validate a CC number.
You can enter 'exit' anytime to quit.
Please enter a CC number to validate: 4111111111111111
Valid!
Please enter a CC number to validate: 1234567890123456
Invalid!
Please enter a CC number to validate: exit
```
