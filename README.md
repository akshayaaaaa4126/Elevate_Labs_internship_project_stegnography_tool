# 🕵️‍♂️ Steganography Tool — Elevate Labs Internship Project
 

---

> 🔐 A dual-approach steganography solution developed as part of the **Elevate Labs Internship** program.  
> This project includes both a **local Python GUI tool** and a **modern web version** for embedding and extracting files/text from images.

---

## 📦 Project Overview

This repository contains **two implementations** of the steganography tool:

1. **Python GUI Tool (Tkinter)** — Offline desktop version with AES encryption.  
2. **Web App (React + TypeScript)** — Modern, browser-based version (no backend needed).

---

## 🧩 Method 1: Python GUI Tool

A desktop GUI application built using **Python’s Tkinter framework**.  
It provides offline steganography with optional **AES-GCM encryption**.

### 🔧 Features
- 🖼️ Supports **PNG/BMP (lossless) image formats**  
- 🔒 Optional **AES-GCM encryption with passphrase**  
- 📄 Embed and extract **text or entire files**  
- 💬 Drag-and-drop support via `tkinterdnd2`  
- 🎨 Simple, user-friendly GUI with status updates  

---

### 🚀 Getting Started (Python)

```bash
# Clone the repository
git clone https://github.com/username/Elevate_Labs_Internship_Project_Steganography_Tool.git
cd Elevate_Labs_Internship_Project_Steganography_Tool/python

# Install dependencies
pip install pillow pycryptodome tkinterdnd2

# Launch the GUI tool
python stego_tool.py
```

---

## ⚛️ Method 2: Web Tool (React + TypeScript + Vite)

A modern, **interactive web-based steganography tool** that runs entirely in your browser.

### 🔧 Features
- ⚡ Lightning-fast UI with **React + TailwindCSS**  
- 🔐 Secure **AES-GCM encryption/decryption**  
- 📂 Drag-and-drop support for **images/files**  
- 📤 Extract hidden messages/files directly in the browser  
- 🌍 Hosted version available for instant access  

---

### 🚀 Getting Started (Web App)

```bash
# Navigate to the web app project
cd Elevate_Labs_Internship_Project_Steganography_Tool/project

# Install dependencies
npm install

# Start local development server
npm run dev
```

👉 Build for production:
```bash
npm run build
```

---

## 📁 Project Structure

```
Elevate_Labs_Internship_Project_Steganography_Tool/
├── python/               # Python GUI version
│   └── stego_tool.py     # Main Tkinter GUI
│
├── project/              # React + TypeScript version
│   ├── src/              # React source files
│   ├── steganography.js  # Image encoding/decoding logic
│   ├── app.js
│   └── ...
```

---

## 📸 Screenshots
### Web Version
### Main Window
![Screenshot 1](https://github.com/jagadeep18/Elevate_Labs_Internship_Project_Steganography_Tool/blob/main/Screenshot_1.png?raw=true)

![Screenshot 2](https://github.com/jagadeep18/Elevate_Labs_Internship_Project_Steganography_Tool/blob/main/Screenshot_2.png?raw=true)

---

## 🛠 Dependencies

### ✅ Python Version
- Python 3.x  
- Pillow  
- PyCryptodome  
- Tkinter (built-in)  
- tkinterdnd2 (optional, for drag-and-drop)  

### ✅ Web Version
- React + TypeScript + Vite  
- TailwindCSS  
- JavaScript (steganography logic)  

---

## ⚠️ Notes
- 📌 Use **PNG or BMP files only** — JPEG may corrupt hidden data.  
- 🔐 AES encryption is **optional but highly recommended**.  
- 📂 Drag-and-drop is enabled in both versions (requires `tkinterdnd2` in Python).  

---

## 👨‍💻 Author
Developed by *Bollineni Akshaya**  
🧑‍💻 Internship Project @ **Elevate Labs**
