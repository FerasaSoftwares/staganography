# 🔐 StegoLab — Steganography Demo Tool

A fully self-contained **browser-based steganography application** built in a single HTML file.
This tool allows users to **hide, extract, and detect secret data inside images** using the **LSB (Least Significant Bit)** technique.

> ⚠️ Built for educational and demonstration purposes (College Expo Project)

---

## 🚀 Features

### 🔐 1. Hide Message (Encryption)

* Upload an image (PNG, JPG, WEBP)
* Enter a secret message
* Embed the message invisibly inside the image
* Download the encoded image as PNG

---

### 🔓 2. Reveal Message (Decryption)

* Upload an encoded PNG image
* Automatically extracts hidden message
* Detects whether image contains valid embedded data

---

### 🕵️ 3. Detect Steganography

* Analyze any image (PNG/JPG)
* Uses **LSB statistical analysis**
* Shows:

  * Pixel count
  * LSB distribution (R, G, B channels)
  * Chi-square anomaly score
* Provides verdict:

  * Likely Clean ✅
  * Possibly Contains Data ⚠️
  * Likely Contains Hidden Data ❌

---

### 🧠 4. How It Works (Educational Section)

* Explains LSB steganography visually
* Binary-level demonstration
* Real-world usage examples

---

## ⚙️ How It Works

This project uses **Least Significant Bit (LSB) Steganography**:

* Each pixel has RGB values (0–255)
* The last bit (LSB) is modified to store data
* Changes are **visually invisible**

### Example:

Original:

```text
11001000
```

Modified:

```text
11001001
```

👉 Only 1-bit change → no visible difference

---

## 📂 Project Structure

This is a **single-file application**:

```text
index.html
```

Contains:

* UI (HTML + CSS)
* Logic (JavaScript)
* Image processing using Canvas API

No backend required.

---

## ▶️ How to Run

### Option 1: Open directly

```bash
Open index.html in browser
```

### Option 2: Use Live Server (recommended)

```bash
Right click → Open with Live Server
```

---

## ⚠️ Important Notes

* ✅ Works best with **PNG images**
* ❌ JPEG may destroy hidden data due to compression
* ⚠️ Detection is **statistical (not 100% accurate)**

---

## 🧪 Demo Capabilities

This tool demonstrates:

* Data hiding using pixel manipulation
* Binary-level encoding
* Image-based covert communication
* Basic steganography detection techniques

---

## 🔐 Security Disclaimer

This project is created for:

* Educational purposes
* Cybersecurity awareness
* Demonstrations

Do **NOT** use for:

* Illegal data hiding
* Malicious activities

---

## 🛠️ Technologies Used

* HTML5
* CSS3 (Custom UI + Animations)
* Vanilla JavaScript
* Canvas API (Image Processing)

---

## 🎯 Future Improvements

* Multi-image batch processing
* AES encryption before embedding
* Drag & drop improvements
* Better AI-based detection

---

## 👨‍💻 Author

Developed by **Fayiz**

---

## ⭐ Support

If you found this project useful:

* Star ⭐ the repository
* Share with others
* Contribute improvements

---

## 📌 Project Type

* Cybersecurity Demo
* Steganography Tool
* College Expo Project

---

> “What you see is not always what you get — data can hide in plain sight.”
