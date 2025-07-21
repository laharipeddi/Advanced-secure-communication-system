# Secure Data Transmission using Symmetric Encryption and Steganography

This project implements a dual-layered security system for transmitting confidential data. It combines symmetric encryption for data confidentiality with modified Least Significant Bit (LSB) steganography to conceal the existence of the data inside images. A user-friendly Flask web interface allows encryption, embedding, extraction, and decryption operations.

---

## Features

- Custom-built symmetric encryption using XOR and circular bit shifts.
- Modified LSB steganography with dynamic bit embedding across RGB channels.
- Flask-based web interface for user interaction.
- Accurate recovery of original data from stego images.
- Compatible with PNG, JPG, and JPEG formats.
- Cross-platform: works on Windows, Linux, and macOS.
---

##  Tech Stack

- **Language:** Python 3.7+
- **Libraries:** OpenCV, NumPy, Flask, Pillow
- **Interface:** Flask web framework with HTML templates
- **Tools:** Visual Studio Code / PyCharm

---
## Project Structure

- app.py # Main Flask application
-  Encryption.py # Custom symmetric encryption logic
- ecryption.py # Decryption logic
- steanov_2.py # Modified LSB steganography functions
- Preprocessing.py # Binary conversion utilities
- string_to_binary.py # Bitwise helpers
- templates/ # HTML files for the web interface
- static/ # CSS, JS, or image assets
- README.md # Project documentation
## How To Run
- git clone https://github.com/laharipeddi/secure-data-transmission.git
- cd secure-data-transmission
- pip install -r requirements
- Run python app.py
- open in browser http://localhost:5000
