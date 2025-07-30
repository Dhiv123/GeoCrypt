# 🔐 GeoCrypt: Location-Locked Decryption Tool

**GeoCrypt** is a web-based encryption-decryption system that ensures data can only be decrypted at a specific physical location. It uses [ChaCha20Poly1305](https://en.wikipedia.org/wiki/ChaCha20) encryption, geofencing with the Haversine formula, and PBKDF2 key derivation to prevent data interception or leakage during transmission.

[![Try GeoCrypt Live](https://geoencryption-kw33.onrender.com/login)

---

## 🚀 Features

- 🔒 End-to-end secure encryption using ChaCha20Poly1305
- 🌍 Location-bound decryption with Haversine-based geofencing
- 🔑 Password-derived keys with PBKDF2 for enhanced security
- 📂 Supports both message and file encryption
- 🧭 Only decrypts if you're within the allowed radius of the encrypted location

---

## 🖼️ Screenshots


<img width="1918" height="865" alt="image" src="https://github.com/user-attachments/assets/1a163524-4f59-4e47-bf5a-941fef56b6dc" />

---

## 🛠️ Technologies Used

- Python + Flask
- HTML/CSS/JS
- ChaCha20Poly1305 (from `cryptography` library)
- Geolocation APIs
- Haversine distance check

---

## 📦 How to Run Locally

```bash
git clone https://github.com/Dhiv123/geocrypt.git
cd geocrypt
pip install -r requirements.txt
python app.py
