# 🆔 National ID Card Information Extractor

This project is an AI-powered application that extracts information from Iranian national ID cards using deep learning and image processing techniques.

## 🚀 Overview

By using a YOLO-based object detection model, the system detects and isolates key regions on the ID card (such as name, ID number, birth date, etc.), then applies OCR (Optical Character Recognition) to extract the textual information.

## 🧠 Technologies Used

- **YOLO (You Only Look Once)** – For detecting regions of interest (ROIs)  
- **OpenCV** – For image pre-processing and contour handling  
- **Tesseract OCR** – For text extraction from image regions  
- **Python** – Main programming language  
- **Deep Learning** – For object detection and image analysis  

## 📷 Sample Workflow

1. Upload an image of a national ID card.
2. YOLO detects text fields.
3. Image preprocessing is applied (e.g., resizing, thresholding).
4. OCR extracts data from detected regions.
5. Structured output (JSON or text) is returned.
