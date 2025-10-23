# Caesar-Cipher-in-Python
🗝️ Caesar Cipher Program  A simple Python program that encrypts and decrypts text using the Caesar Cipher algorithm. This project demonstrates basic encryption logic, modular programming, and user input handling in Python.
📘 Overview

The Caesar Cipher is one of the earliest known encryption techniques. It works by shifting each letter in a message by a fixed number of positions in the alphabet.

This program allows users to:
Encrypt a message using a custom shift key.
Decrypt a message back to its original form.
Keep non-alphabetic characters (spaces, punctuation) unchanged.

⚙️ How It Works
The user chooses whether to encrypt or decrypt a message.
The program asks for a message and a numerical shift key.
Each letter in the message is shifted by the given number of positions.
The processed (encrypted or decrypted) text is displayed.

🧩 Features
Handles both uppercase and lowercase letters.
Keeps symbols and numbers unchanged.
Validates inputs for correct data types.
Loops until the user chooses to exit.

▶️ Usage
Run the program directly in your terminal:
python caesar_cipher.py

You’ll then be guided through:
Choosing encryption or decryption.
Entering your message.
Providing a numeric shift key.


Example interaction:

--- Caesar Cipher Program 🗝️ ---
Do you want to (e)ncrypt or (d)ecrypt the message? e
Enter the message to encrypt: hello world
Enter the shift key (a number, e.g., 3): 3

------------------------------------
Original message:  hello world
Processed message: khoor zruog
------------------------------------

Do you want to process another message? (yes/no): no
Goodbye!
