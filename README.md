# RSA Cryptography Project

This project explores the RSA cryptosystem and the mathematical ideas behind it.  
The goal was to understand how concepts from **number theory** are used in modern cryptography and to implement the algorithms in Python.

## What the project includes

The project focuses on computing modular exponentiation efficiently, which is a key part of the RSA algorithm.

Implemented methods include:

- Modular exponentiation using the **square-and-multiply method**
- **Montgomery ladder**, which performs a constant number of operations per bit and helps prevent timing attacks
- **Multiplicative splitting modulo N**, used to simplify modular computations

## Mathematical background

The implementation is based on several concepts from **number theory**, including: modular arithmetic, Euler's totient function, modular inverses, properties of prime numbers, efficient exponentiation algorithms

## Files

- `rsa_code.ipynb` – Python implementation of the algorithms  
- `rsa.pdf` – presentation explaining the mathematical ideas and algorithms

## Motivation

This project was created as part of my study of cryptography with the aim of connecting mathematical theory with practical algorithm implementation.
