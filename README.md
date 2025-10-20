# 🔐 AES Encryption-Decryption Web Tool

A **100% client-side AES Encryption & Decryption tool** built with **HTML, CSS, and JavaScript (CryptoJS library)**.  
Secure your sensitive data like passwords, API keys, or messages with **End-to-End Encryption (E2EE)**.

---

⚡ Features

🔐 End-to-End AES Encryption
💻 100% Client-side (No server or network calls)
🎨 Beautiful Terminal-style Interface
🧠 Auto Key Derivation (SHA-256 for key length accuracy)
🧩 Supports Base64 / Hex formats
🧰 Works for 128, 192, and 256-bit encryption

---

## 🧩 How It Works

1. **Input Data** – Enter your plaintext message or password.
2. **Key Derivation** – Secret key is hashed using SHA-256 to match AES key length.
3. **AES Encryption** – Encrypts the message using AES-CBC with your key & IV.
4. **Output** – Shows encrypted text in Base64 or Hex.
5. **AES Decryption** – Decrypts back to plaintext using the same key & IV.

---

## ⚡ Example Usage

🔹 ENCRYPTION

INPUT_DATA -	Jai Shree Ram
CIPHER_MODE -	CBC
PADDING_SCHEME - 	PKCS5Padding
INIT_VECTOR (IV) -	9876543210abcdef
KEY_SIZE_BITS -	128
SECRET_KEY - 	bappa1234567890
OUTPUT_FORMAT -	BASE64
🔹 OUTPUT
> SUCCESS: 1Xvk0Vb8PoTSnNd8eDZZng==_

🔹 DECRYPTION

ENCRYPTED_DATA	- 1Xvk0Vb8PoTSnNd8eDZZng==
CIPHER_MODE -	CBC
PADDING_SCHEME -	PKCS5Padding
INIT_VECTOR (IV) -	9876543210abcdef
KEY_SIZE_BITS	- 128
SECRET_KEY -	bappa1234567890
OUTPUT_FORMAT -	PLAINTEXT
🔹 OUTPUT
> SUCCESS: Jai Shree Ram



