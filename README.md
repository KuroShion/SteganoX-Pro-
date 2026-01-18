# 🔐 SteganoX Pro

**SteganoX Pro** is a modern, secure steganography application that allows you to hide files or messages inside images using strong cryptography and LSB steganography.

It is designed to be **easy to use**, **secure**, and **powerful**, with a clean GUI and advanced analysis tools.

---

## ✨ Features

### 🔐 Encryption / Hiding
- Hide **files or text messages** inside images
- Uses **ChaCha20-Poly1305 authenticated encryption**
- LSB steganography with **randomized distribution**
- Multiple modes:
  - Beginner
  - Balanced
  - Stealth
  - Forensic
  - Max Capacity
  - Custom
- Password strength meter
- Capacity & risk analysis
- Progress bar and background processing
- Drag & drop support
- Output folder quick-open button

### 🔓 Decryption / Extraction
- Extract hidden payload from images
- Supports:
  - File payload recovery
  - Text message recovery
- Save extracted data to file
- Password protected extraction

### 🧪 Steganography Scan / Detection
- Analyze images for hidden data using:
  - Shannon entropy
  - LSB noise analysis
- Shows:
  - Suspicion score
  - Verdict (Clean / Possibly Hidden / Highly Suspicious)
- Image preview and drag & drop support

### 🎨 UI & UX
- Light / Dark theme
- Remembers user settings
- Drag & drop everywhere
- Image preview panel
- Responsive layout
- Auto maximized on launch

---

## 🛡️ Security

- Encryption: **ChaCha20-Poly1305 (AEAD)**
- Steganography: **LSB with randomized bit distribution**
- Encrypted payload is authenticated and tamper-proof
- No plaintext is ever written into the image

---

## 🖥️ Screenshots

> (Add screenshots here)

---

## 📦 Requirements

- Python 3.9+
- Dependencies:

```bash
pip install pyside6 pillow pycryptodome
