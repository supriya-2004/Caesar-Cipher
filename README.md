# 🔐 Caesar Cipher Project

## 📌 Problem Statement
This project is about creating a Python program that can encrypt or decrypt text using the Caesar cipher algorithm. The program should allow users to input a message and a shift value to perform encryption and decryption.

## ✨ Features
- 🔒 Encrypts plaintext using a shift key (1-26).
- 🔓 Decrypts ciphertext back to plaintext using the same shift key.
- 🛡️ Preserves non-alphabet characters without modification.
- 🔠 Works with both uppercase and lowercase letters.

## ⚙️ How It Works
- Each letter in the input text is replaced by a letter some fixed number of positions down the alphabet.
- 🔄 The shift wraps around when reaching the end of the alphabet (e.g., shifting 'z' by 1 results in 'a').
- 🔄 The decryption process reverses this transformation.

## 🛠️ Usage

### 1️⃣ Run the script:
```bash
python caesar_cipher.py
```

### 2️⃣ Choose encryption or decryption:
- ✉️ Enter **'e'** for encryption.
- 🔓 Enter **'d'** for decryption.

### 3️⃣ Provide a key:
- 🔢 The shift key must be a number between 1 and 26.

### 4️⃣ Enter text:
- 📝 Input the message you want to encrypt or decrypt.

## 🔍 Example
### 🔐 Encryption
```
Do you want to encrypt or decrypt?
e/d: e

ENCRYPTION MODE
Enter the key between 1 to 26: 3
Enter text to encrypt: hello
CIPHERTEXT: khoor
```

### 🔓 Decryption
```
Do you want to encrypt or decrypt?
e/d: d

DECRYPTION MODE
Enter the key between 1 to 26: 3
Enter text to decrypt: khoor
PLAINTEXT: hello
```

## 📝 Implementation Details
- Uses a predefined alphabet (`abcdefghijklmnopqrstuvwxyz`) for letter lookup.
- 🏗️ Handles both uppercase and lowercase inputs by converting all letters to lowercase.
- ✨ Non-alphabet characters remain unchanged.
