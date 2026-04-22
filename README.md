# 📄 OCR-Based Receipt Scanner using Tesseract & EasyOCR

## 👤 Author

**Haseeb Sheikh**

---

## 📌 Project Overview

This project demonstrates how to extract text from receipt images using Optical Character Recognition (OCR). It uses two powerful OCR engines: **Tesseract OCR** and **EasyOCR**, combined with **OpenCV preprocessing** techniques to improve text extraction accuracy.

The project is implemented in a Kaggle Notebook environment and does not require any external dataset, as sample receipts are generated programmatically.

---

## 🎯 Objectives

* Extract text from receipt images
* Compare OCR performance (Tesseract vs EasyOCR)
* Improve accuracy using image preprocessing
* Analyze confidence scores
* Build a basic OCR comparison pipeline

---

## 🛠️ Technologies Used

* Python
* Tesseract OCR
* EasyOCR
* OpenCV
* NumPy
* Pandas
* Matplotlib
* PIL (Python Imaging Library)

---

## ⚙️ Features

* ✅ Automatic receipt image generation (no dataset required)
* ✅ Text extraction using Tesseract OCR
* ✅ Text extraction using EasyOCR
* ✅ Confidence score analysis
* ✅ Image preprocessing (grayscale, blur, thresholding)
* ✅ Before vs After OCR comparison
* ✅ OCR comparison function

---

## 📂 Project Structure

```
📁 OCR-Receipt-Scanner
 ┣ 📄 notebook.ipynb
 ┣ 📄 README.md
 ┗ 📄 sample_receipt.jpg
```

---

## 🚀 How to Run (Kaggle)

1. Go to Kaggle and create a new notebook
2. Copy and paste the provided code into cells
3. Run all cells step by step
4. The notebook will:

   * Generate a sample receipt
   * Extract text using OCR
   * Apply preprocessing
   * Compare results

---

## 📊 Results

* Preprocessing improves OCR accuracy
* EasyOCR performs better on noisy images
* Tesseract provides structured output with confidence scores

---

## 🔮 Future Improvements

* Extract structured data (Date, Total, Items) using Regex
* Add support for multiple languages
* Build a web/mobile app for real-time scanning
* Improve preprocessing pipeline

---

## 📷 Sample Output

The system generates a receipt image and extracts:

* Store Name
* Date
* Items
* Total Amount

---

## 📌 Conclusion

This project successfully demonstrates how OCR combined with image preprocessing can significantly improve text extraction accuracy from receipts. It provides a solid foundation for building document intelligence systems.

---

## ⭐ Acknowledgment

This project is part of the **Introduction to Applied Artificial Intelligence** course lab work.

---
