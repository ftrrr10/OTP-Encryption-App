# Desktop App for One-Time Pad (OTP) Encryption

This is an educational desktop application designed to demonstrate the principles of message encryption and decryption using the **One-Time Pad (OTP)** algorithm. 
The project was developed as an academic requirement for a Cryptography course. 

The primary goal of this application is to provide a practical and interactive tool for students and users to understand how OTP works, from key generation to the final decryption process.

## About the Algorithm: One-Time Pad (OTP)

The One-Time Pad is a classical cryptography technique renowned for being theoretically unbreakable. As proven by Claude Shannon, it offers **perfect secrecy** on the condition that its core principles are strictly followed. 

The encryption and decryption processes are based on a simple **XOR logical operation**. 

### Key Principles of OTP
* **Random Key**: The key must be perfectly random. 
* **Same Length**: The key's length must be equal to the message's length. 
* **Single Use**: The key must never be used more than once. 

## ✨ Application Features

This application provides a user-friendly graphical interface (GUI) to perform OTP operations locally. 

* **Encrypt & Decrypt Text**: Users can input plaintext to be encrypted or ciphertext to be decrypted.
* **Automatic Key Generation**: The app can generate a cryptographically secure random key with the same length as the input message. 
* **Save & Load Keys**: Users can save a generated key to a local file and load a key from a file for decryption. 
* **Interactive Interface**: A simple and intuitive GUI built with Tkinter allows users to easily perform all actions and see the results in real-time. 
* **Offline Operation**: The application runs entirely offline as a standalone desktop program, requiring no internet connection. 

## 🛠️ Tech Stack

The application was built using standard Python libraries, requiring no external dependencies. 

* **Programming Language**: **Python** (Version 3.8+). 
* **GUI Library**: **Tkinter**, Python's standard GUI toolkit. 
* **Secure Key Generation**: Python's built-in **`secrets`** module was used to generate cryptographically strong random keys. 
* **File System Interaction**: The built-in **`os`** module is used for file-related operations. 



## 👥 Authors

This project was developed by :
* Pitria Wanda Riza Putri 
