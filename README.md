# rsa-cryptanalysis
Implementing RSA encryption from scratch in C++ and attacking weak keys using Fermat's factorisation method. Documenting the exact key-size boundary where attacks fail.
# RSA Cryptanalysis — Attacking Weak Keys

## What is this?
RSA encryption protects every HTTPS connection on the internet.
Its security rests on one fact: factoring the product of two
large primes is computationally hard.
This project implements RSA from scratch in C++ and attempts
to break weak keys using Fermat's factorisation method.

## What I am doing
- Implementing RSA key generation, encryption, decryption in C++
- Attacking weak keys where primes p and q are chosen close together
- Finding the exact key-size boundary where Fermat factorisation fails
- Documenting the mathematics of why production RSA is unbreakable

## Why this matters
Real-world RSA implementations have been broken this way.
This is not a textbook exercise. It replicates documented
vulnerabilities in real deployed cryptographic systems.

## Structure
/src        — RSA implementation and attack code in C++
/logs       — weekly progress logs
/writeup    — working draft of the research write-up

## Mathematical prerequisites I am covering
- Modular arithmetic
- Euler's totient function
- Fermat's little theorem
- GCD and the Euclidean algorithm
- Prime factorisation and its computational limits

## Status
Project begins [PUT TODAY'S DATE]. All progress committed daily.

## Contact
[your email]
