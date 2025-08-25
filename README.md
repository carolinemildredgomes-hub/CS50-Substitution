# CS50 Substitution

![C](https://img.shields.io/badge/language-C-blue)
![CS50](https://img.shields.io/badge/CS50-Harvard-red)

## Description

A C program that encrypts messages using a **substitution cipher**. Users provide a 26-character key that maps each letter of the alphabet to a unique substitute letter. The program preserves uppercase and lowercase letters and leaves non-letter characters unchanged.

---

## How to Compile and Run

1. Download `substitution.c` from this repository.  
2. Open a terminal and navigate to the folder containing `substitution.c`.  
3. Compile the program:

```bash
gcc -o substitution substitution.c cs50.c

Run the program with a 26-character key:
./substitution YTNSHKVEFXRBAUQZCLWDMIPGJO

Enter your plaintext when prompted:
plaintext: Hello, World!

The program outputs:
ciphertext: Eaqqt, Tqkbf!

Example
Input: Hello, World!
Key: YTNSHKVEFXRBAUQZCLWDMIPGJO
Output: Eaqqt, Tqkbf!

Key Notes / Learning Outcomes

Implements a substitution cipher with user-provided key.

Validates key for length, letters only, and uniqueness.

Handles uppercase and lowercase letters.

Leaves numbers and punctuation unchanged.

Demonstrates loops, conditionals, string manipulation, and character arithmetic in C.

