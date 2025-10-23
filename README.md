# Assessment Winter 25/26 (Year 4️⃣)
**Name:** Tomás Pettit

**Student ID:** G00419414

**Course:** Software Development

**Module:** Computational Theory 💻

## Description

## References

### Problem 1
Implement the following functions in Python.
Use numpy to ensure that all variables and values are treated as 32-bit integers.
These functions are defined in the Secure Hash Standard [see page 10](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf).

1. `Parity(x, y, z)`
2. `Ch(x, y, z)`
3. `Maj(x, y, z)`
4. `Sigma0(x)` - written as $\Sigma_0^{\{256\}}(x)$ in the standard.
5. `Sigma1(x)` - written as $\Sigma_1^{\{256\}}(x)$ in the standard.
6. `sigma0(x)` - written as $\sigma_0^{\{256\}}(x)$ in the standard.
7. `sigma1(x)` - written as $\sigma_1^{\{256\}}(x)$ in the standard.

See: [Problem 1: Binary Words and Operations](https://github.com/tomaspettit/CT-G00419414/blob/main/problems.ipynb)

### Problem 2
Use numpy to calculate the constants listed at the bottom of [page 11](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf) of the Secure Hash Standard, following the steps below.
These are the first 32 bits of the fractional parts of the cube roots of the first 64 prime numbers.

1. Write a function called `primes(n)` that generates the first n prime numbers.

2. Use the function to calculate the cube root of the first 64 primes.

3. For each cube root, extract the first thirty-two bits of the fractional part.

4. Display the result in hexadecimal.

5. Test the results against what is in the Secure Hash Standard.

See: [Problem 2: Padding](https://github.com/tomaspettit/CT-G00419414/blob/main/problems.ipynb)

### Problem 3:

Write a [generator function](https://realpython.com/introduction-to-python-generators/) `block_parse(msg)` that processes messages according to section 5.1.1 and 5.2.1 of the Secure Hash Standard.
The function should accept a [bytes object](https://realpython.com/python-bytes/) called `msg`.
At each iteration, it should yield the next 512-bit block of `msg` as a bytes object.
Ensure that the final block (or final two blocks) include the required padding of `msg` as specified in the standard.
Test the generator with messages of different lengths to confirm proper padding and block output.

See: [Problem 3: Fractional Parts of Cube Roots](https://github.com/tomaspettit/CT-G00419414/blob/main/problems.ipynb)

### Problem 4

### Problem 5
