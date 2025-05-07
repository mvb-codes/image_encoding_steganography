# 🔐 Image Steganography Tool

A lightweight Python tool to conceal and extract small files within PNG images using the Least Significant Bit (LSB) technique.

---

## 📦 Project Description

Steganography is the art of hiding information within innocuous media files. This project provides a simple and effective implementation of image-based steganography in Python. By modifying the least significant bits of image pixels, it becomes possible to embed arbitrary files—such as text, documents, or code—inside PNG images without noticeable distortion.

This tool is particularly useful for educational purposes, research in data privacy, or lightweight data concealment tasks.

---

## 🛠️ Features

- ✅ Hide any file format (text, PDF, script, etc.)
- ✅ Lossless PNG-based encoding and decoding
- ✅ Command-line interface for ease of use
- ✅ Bit-level control using `numpy` for efficient operations
- ✅ Includes file length header for precise extraction
- 🚫 No external APIs or cloud dependencies
- 🧪 Tested on files up to ~95 KB with 512x512 PNG images

---

## 🚀 Getting Started

### 🔧 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/image-steganography.git
cd image-steganography
pip install -r requirements.txt
