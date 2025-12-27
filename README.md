# Computational Theory – SHA-256 Assignment

**Author:** Sarah O'Connor  
**Student ID:** G00423847  
**Module:** Computational Theory  

## Overview
This repository contains my submission for the Computational Theory assessment.  
The work explores and implements key components of the SHA-256 cryptographic hash function as defined in the *Secure Hash Standard (FIPS 180-4)*.

All problems are completed in a single Jupyter notebook, with explanations and tests included alongside the code.

The assignment focuses on:
- bitwise logical functions used in SHA-256,
- generation of SHA-256 round constants from prime numbers,
- message padding and block parsing,
- implementation of the SHA-256 compression function,
- and a dictionary attack on unsalted SHA-256 password hashes.

## Setup and Running the Notebook
1. Clone the repository:
```
   git clone https://github.com/sarahoconnor10/computational_theory.git
```
2. Install dependencies:
```
    pip install -r requirements.txt
```
3. Open the notebook:
```
    jupyter notebook problems.ipynb
```
4. Run cells from top to bottom

---


**Note** - this file relies on an external txt file (2000-most-used-passwords.txt) and must remain in the same directory for problem 5 to run correctly.