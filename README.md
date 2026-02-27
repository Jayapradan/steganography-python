# Python Image Steganography (LSB + AES)

This project performs image steganography using Least Significant Bit (LSB) technique and AES encryption.

## Features
- Hide any file (ZIP, PDF, TXT, etc.)
- AES-256 encryption
- PBKDF2 password key generation
- Works on Google Colab
- Encode & decode image files

## How to Run (Colab)
1. Upload `steg.py`
2. Create secret.zip
3. Create orig.png
4. Run encode()
5. Download output.png
6. Upload output.png
7. Run decode()

## Files Included
- steg.py (main Python code)
- orig.png (original image)
- output.png (image with hidden data)
