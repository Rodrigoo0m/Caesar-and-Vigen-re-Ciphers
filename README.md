# Caesar and Vigenère Ciphers

This repository contains Python implementations of two classical encryption techniques: Caesar Cipher and Vigenère Cipher. Each cipher has its encryption and decryption functions, along with interactive menus for user input.

## Contents

- [Caesar Cipher](#caesar-cipher)
- [Vigenère Cipher](#vigenère-cipher)
- [Usage](#usage)
- [How to Run](#how-to-run)
- [Contributing](#contributing)

## Caesar Cipher

The Caesar Cipher is a substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

### Functions:

- `caesar_cipher(text, key)`: Encrypts `text` using the Caesar Cipher with the given numerical `key`.
- `caesar_decipher(ciphertext, key)`: Decrypts `ciphertext` encrypted with Caesar Cipher using the reverse `key`.

### Example:

```python
plaintext = "Hello, World!"
key = 3
encrypted_text = caesar_cipher(plaintext, key)
decrypted_text = caesar_decipher(encrypted_text, key)
print("Encrypted:", encrypted_text)
print("Decrypted:", decrypted_text)

#Vigenère Cipher
The Vigenère Cipher is a method of encrypting alphabetic text by using a keyword and rearranging letters based on a series of Caesar shifts.```

###Functions:
vigenere_cipher(text, key): Encrypts text using the Vigenère Cipher with the given key.
vigenere_decipher(ciphertext, key): Decrypts ciphertext encrypted with Vigenère Cipher using the reverse key.

#Example:
 
```python
plaintext = "Hello, World!"
keyword = "KEY"
encrypted_text = vigenere_cipher(plaintext, keyword)
decrypted_text = vigenere_decipher(encrypted_text, keyword)
print("Encrypted:", encrypted_text)
print("Decrypted:", decrypted_text)
```

#Usage
The ciphers are implemented as functions and can be used programmatically or through interactive menus provided in main_menu(), caesar_cipher_menu(), and vigenere_cipher_menu().

##How to Run
To run the interactive menu:

Clone the repository:

bash
Copiar código
git clone https://github.com/your-username/caesar-vigenere-ciphers.git
cd caesar-vigenere-ciphers
python ciphers.py

Follow the prompts to encrypt or decrypt text using either the Caesar or Vigenère cipher.










