# 📱 QR Code Generator

> A sleek, dark-themed web application to generate downloadable QR codes for any URL.

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Tech Stack](https://img.shields.io/badge/Stack-HTML%20|%20CSS%20|%20JavaScript-yellow)

## 📖 Overview
This project is a simple yet powerful tool that allows users to instantly generate QR codes by entering a URL. It features a modern **Dark Mode** interface and uses the `qrcode.js` library to handle generation directly in the browser. Users can also download their generated QR codes as PNG images.

## ✨ Features
- **Instant Generation:** Creates a QR code immediately upon form submission.
- **Dark Mode UI:** A modern, eye-friendly dark theme built with custom CSS.
- **Download Capability:** Save the generated QR code as a `qrcode.png` file with a single click.
- **Responsive Design:** Clean, centered layout that works on different screen sizes.
- **Smart Reset:** Automatically clears the previous QR code when you start typing a new URL.

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3 (Grid & Flexbox)
- **Scripting:** Vanilla JavaScript (ES6)
- **Library:** [qrcode](https://www.npmjs.com/package/qrcode) (via CDN) for canvas generation.
- **Fonts:** 'Poppins' from Google Fonts.

## 🚀 How to Use
1. **Enter URL:** Type or paste a website link into the input field (e.g., `https://google.com`).
2. **Generate:** Click the **"Generate QR Code"** button.
3. **View:** The QR code will appear instantly in the center card.
4. **Download:** Click the **"Download QR"** button to save the image to your device.

## 📂 Project Structure
```text
qrcodegenerator/
├── home.html         # Main application structure
├── style.css         # Dark theme styling and layout
├── script.js         # Logic for QR generation and downloading
└── .gitignore        # Ignored files
