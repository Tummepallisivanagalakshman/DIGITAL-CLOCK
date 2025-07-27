# 🔐 Secure Image Messenger – Image Encryption Using Steganography

A Python-based GUI application that hides secret messages within images using LSB (Least Significant Bit) steganography. Messages are encrypted using Fernet symmetric encryption before being embedded, ensuring double-layered security.

---

## 🖥️ GUI Features

- ✅ Toggle between Encode and Decode modes
- 🖼 Select and display chosen images
- 🔐 Encrypt secret messages using Fernet key
- 🧠 Hide encrypted messages using LSB technique
- 🔓 Decrypt and reveal hidden messages with the key
- 🧾 Key auto-generated and copied to clipboard

---

## 🛠 Tech Stack

- **Python 3.x**
- `tkinter` – for GUI
- `Pillow` – for image processing
- `cryptography` – for message encryption
- `bitarray` – to handle binary message data
- `pyperclip` – to copy keys to clipboard

---
## Run the App
  python app.py

## ⚙️ Installation

1. Clone this repository:
```bash
git clone https://github.com/Tummepallisivanagalakshman/image-encryption-steganography.git
cd image-encryption-steganography


