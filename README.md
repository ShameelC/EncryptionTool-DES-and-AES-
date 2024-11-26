# Encryption and Decryption Tool

A Python-based tool for securely encrypting and decrypting text using AES and DES algorithms. This project provides a simple command-line interface for encrypting and decrypting data. It uses the `cryptography` library for secure encryption and `ipywidgets` for handling the user interface.

---

## **Features**
- Supports **AES** and **DES** encryption algorithms.
- Password-based encryption with secure key derivation using PBKDF2HMAC.
- Ensures data security with padding and initialization vectors.
- Easy-to-use interface for encryption and decryption processes.

---

## **Installation**

### **Prerequisites**
1. Python 3.7 or above installed on your system.
2. Required Python libraries:
   - `cryptography`
   - `ipywidgets` (for the GUI elements)

### **Install Dependencies**
Install the required libraries using pip:
```bash
pip install cryptography ipywidgets

---

## **Encryption:**

  Choose Algorithm (AES/DES): AES
  Enter plaintext to encrypt: Hello World
  Enter password: mysecretpassword
  Encrypted Message: [encrypted_text_here]

---

## **Decryption:**

  Choose Algorithm (AES/DES): AES
  Enter ciphertext to decrypt: [encrypted_text_here]
  Enter password: mysecretpassword
  Decrypted Message: Hello World
