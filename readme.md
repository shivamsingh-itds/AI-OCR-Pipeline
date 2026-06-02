# OCR Image Processing Using EasyOCR and PaddleOCR

## Project Overview

This project performs Optical Character Recognition (OCR) on a collection of images using two different OCR frameworks:

* EasyOCR
* PaddleOCR

The objective is to extract text from different image categories and compare OCR performance while generating structured outputs in Excel format.

Developed as part of an AI Internship OCR Assignment.

---

## Project Modules

### 1. Car Plate Recognition (EasyOCR)

EasyOCR was used to extract vehicle registration numbers from car plate images.

Features:

* License plate text extraction
* Multiple image processing
* Confidence-based OCR detection
* Excel report generation

---

### 2. Voltage Display Recognition (PaddleOCR)

PaddleOCR was used for extracting numerical values from voltage meter and digital display images.

Features:

* Digital display OCR
* Image preprocessing using OpenCV
* Text detection and recognition
* Structured Excel output

---

## Project Structure

```text
OCR_Task/
│
├── Car_Plate_EasyOCR.ipynb
├── Voltage_PaddleOCR.ipynb
│
├── Car_Plate_Results.xlsx
├── Voltage_OCR_Results.xlsx
│
├── Car_Images/
├── Voltage_Images/
│
└── README.md
```

---

## Technologies Used

* Python 3.10
* EasyOCR
* PaddleOCR
* PaddlePaddle
* OpenCV
* Pandas
* Matplotlib
* OpenPyXL

---

## OCR Workflow

```text
Input Image
      ↓
Image Preprocessing
      ↓
OCR Engine
(EasyOCR / PaddleOCR)
      ↓
Text Extraction
      ↓
Result Validation
      ↓
Excel Generation
```

---

## Installation

Install required packages:

```bash
pip install easyocr
pip install paddleocr
pip install paddlepaddle
pip install opencv-python
pip install pandas
pip install openpyxl
pip install matplotlib
```

---

## Output Format

| Image Name     | Extracted Text |
| -------------- | -------------- |
| car_01.jpg     | MH01AB1234     |
| voltage_01.jpg | 93.2           |
| voltage_02.jpg | 26.3           |

---

## Applications

* Vehicle Number Plate Recognition
* Voltage Meter Reading
* Digital Display Recognition
* Automated Data Extraction
* OCR Performance Evaluation

---

## Challenges Faced

* OCR accuracy on digital display images
* Image preprocessing requirements
* PaddleOCR and PaddlePaddle version compatibility
* Recognition of low-contrast numerical displays

---

## Future Improvements

* Real-time OCR processing
* Custom-trained OCR models
* Dashboard integration
* Higher accuracy preprocessing pipeline
* Batch automation workflow

---

## Author

Shivam Singh

