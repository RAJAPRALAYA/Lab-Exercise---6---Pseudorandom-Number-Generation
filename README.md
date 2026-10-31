# Lab-Exercise---6---Pseudorandom-Number-Generation

# Aim:
Implementation of Pseudorandom Number Generation Using Standard library.

# Procedure:
1. Import the secrets module: This module provides cryptographically secure random functions.
2. Generate a secure random integer: Use secrets.randbelow(n) to get a random integer between 0 and n-1.
3. Generate a secure random number with a specific bit length: Use secrets.randbits(bit_length) to generate a random number with a given number of bits.
4. Generate a secure random token (hexadecimal): Use secrets.token_hex(nbytes) to generate a secure random token in hex format. The nbytes parameter specifies the number of bytes, and the result will be a string with twice that number of hex characters.
5. Display or use the generated random values: Print or use the generated values for your cryptographic needs.

# Program:
```
import random

minimum = int(input("Enter minimum value: "))
maximum = int(input("Enter maximum value: "))

numbers = list(range(minimum, maximum + 1))

random.shuffle(numbers)

print("Random numbers between", minimum, "and", maximum, "are:")

for num in numbers:
    print(num, end=" ")
```

# Output:
<img width="1317" height="232" alt="image" src="https://github.com/user-attachments/assets/79bc9303-9494-4621-a1b1-e287f2561486" />

# Result:
Thus, Pseudorandom Number Generation Using Standard Library has been executed successfully.
