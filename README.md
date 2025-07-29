# Caesar Cipher

A simple Java implementation of the Caesar Cipher encryption algorithm.

## Description

The Caesar Cipher is a type of substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet. This implementation allows you to encrypt text by shifting letters while preserving non-alphabetic characters.

## Features

- Encrypts text using Caesar Cipher algorithm
- Preserves case (uppercase/lowercase)
- Maintains non-alphabetic characters (spaces, punctuation, numbers)
- Interactive command-line interface

## How to Run

1. **Compile the Java file:**
   ```bash
   javac CaesarCipher.java
   ```

2. **Run the program:**
   ```bash
   java CaesarCipher
   ```

3. **Follow the prompts:**
   - Enter the text you want to encrypt
   - Enter a shift value (0-25)

## Example

```
Enter text to encrypt: Hello World
Enter shift key (0-25): 3
Encrypted text: Khoor Zruog
```

## How It Works

The algorithm shifts each letter by a specified number of positions in the alphabet:
- A shift of 3 transforms 'A' to 'D', 'B' to 'E', etc.
- The algorithm wraps around (Z + 1 = A)
- Non-letter characters remain unchanged

## Requirements

- Java 8 or higher

## Author

AsifaBeedi