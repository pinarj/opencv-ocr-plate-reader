# opencv-ocr-plate-reader

This project demonstrates how to detect vehicle license plates from images and extract their text using classical image processing techniques with OpenCV and optical character recognition (OCR) via Tesseract.

---

## 🔧 Technologies Used
- Python 3
- OpenCV
- Tesseract OCR (via pytesseract)
- NumPy, Matplotlib, Scikit-Image

---

## 📌 Project Overview

The workflow includes:
1. Converting images to grayscale
2. Noise reduction using median filtering
3. Edge detection (Canny & Sobel)
4. Contour detection and filtering based on shape and size
5. Plate region extraction
6. OCR-based character recognition

---

## 📷 Sample Output

An example detection result is provided in the `results/` folder.

```text
#1 → SRK-6TOAS

