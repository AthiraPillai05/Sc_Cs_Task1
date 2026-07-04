# 🔐 Caesar Cipher GUI

A beginner-friendly desktop application built with **Python** and **Tkinter** that encrypts and decrypts messages using the **Caesar Cipher** algorithm.

This project demonstrates the fundamentals of classical cryptography along with GUI development in Python.

---

## 📖 About the Project

The Caesar Cipher is one of the oldest and simplest encryption techniques. It encrypts a message by shifting each letter in the alphabet by a fixed number of positions (called the **shift value**).

This application provides a graphical user interface where users can:

* Enter a message.
* Specify a shift value.
* Encrypt the message.
* Decrypt an encrypted message.
* Copy the output to the clipboard.
* Clear all input fields.

This project was developed as a mini cybersecurity project to understand the basics of encryption and decryption.

---

## ✨ Features

* 🔒 Encrypt text using the Caesar Cipher algorithm
* 🔓 Decrypt encrypted text
* 🖥️ Simple and user-friendly GUI built with Tkinter
* 🔢 Custom shift value
* 📋 Copy encrypted/decrypted text to the clipboard
* 🧹 Clear all input fields
* 🔤 Preserves uppercase and lowercase letters
* ➖ Leaves spaces, numbers, and special characters unchanged

---

## 🛠️ Technologies Used

* Python 3
* Tkinter (Python's built-in GUI library)

---

## 📂 Project Structure

```text
CaesarCipherGUI/
│
├── main.py
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/CaesarCipherGUI.git
```

### 2. Navigate to the project directory

```bash
cd CaesarCipherGUI
```

### 3. Run the application

```bash
python main.py
```

---

## 🧠 How the Caesar Cipher Works

### Encryption

Each letter is shifted **forward** by the specified shift value.

Example:

```
Original Message : HELLO
Shift Value      : 3

Encrypted Text   : KHOOR
```

---

### Decryption

Each letter is shifted **backward** by the same shift value to retrieve the original message.

Example:

```
Encrypted Text : KHOOR
Shift Value    : 3

Original Text  : HELLO
```

---

## 📸 Application Preview

Add a screenshot of your application here after uploading one to your repository.

Example:

```markdown
![Caesar Cipher GUI](screenshot.png)
```

---

## 📚 Concepts Used

* Python Functions
* Conditional Statements (`if`, `else`)
* Loops (`for`)
* String Manipulation
* ASCII Character Conversion using `ord()` and `chr()`
* Modulo Arithmetic (`%`)
* Event-Driven Programming
* Tkinter GUI Components

---

## 🎯 Learning Outcomes

Through this project, I learned:

* The fundamentals of classical cryptography.
* The working of the Caesar Cipher algorithm.
* GUI development using Tkinter.
* Event handling in Python.
* Character encoding using ASCII values.
* Building interactive desktop applications.
---

## 🔮 Future Improvements

* Add input validation for invalid shift values.
* Display error messages using dialog boxes.
* Support encryption and decryption of text files.
* Add Dark Mode.
* Improve the user interface with icons and themes.
* Implement additional classical ciphers such as Vigenère and Playfair.

---

## 👩‍💻 Author

**Athira Pillai**

Cybersecurity Student  Aspiring Cybersecurity Professional

