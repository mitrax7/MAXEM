# MAXEM
Pseudo-Random Number Generator

This work introduces a novel pseudo-random number generation algorithm incorporating modulo arithmetic, XORShift, and entropy modulation. The method is designed to enhance randomness and unpredictability by utilizing bitwise manipulations and dynamic entropy modulation. Experimental results demonstrate the algorithm's performance across various test sets. The algorithm seeks to resolve two of the most common problems of common PRNGs, which are the quality of randomness with selection of an arbitrary seed and the presence of periodic cycles. The findings suggest potential applications in cryptography and statistical simulations.

# MAXEM: A New Pseudo-Random Number Generating Algorithm

This repository contains the source code and example data for the paper:

**"MAXEM: A New Pseudo-Random Number Generating Algorithm with Implementation of Modulo Arithmetic, XORShift, and Entropy Modulation"**  
by **Ramit Sadhukhan** and **Soubhik Chakraborty**  
[Department of Mathematics, Birla Institute of Technology, Mesra]

---

## About

MAXEM is a novel pseudo-random number generating (PRNG) algorithm that integrates:

- **Modulo Arithmetic**
- **XORShift operations**
- **Entropy Modulation using prime-based sequences**

The algorithm addresses key limitations in traditional PRNGs such as the Linear Congruential Generator (LCG) and Mersenne Twister by:

- Avoiding periodic cycle formation
- Supporting arbitrary seed values
- Enhancing randomness with dynamic entropy injection

---

## ⚙️ Requirements

This code uses standard Python 3 libraries and was tested using:

- Python 3.10+
- NumPy
- Matplotlib
- SymPy (optional, for prime utilities)
