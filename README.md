# Image-To-Text
 This project demonstrates how to use Tesseract OCR in combination with OpenCV to extract and highlight text from images. 
 The text is extracted using the Pytesseract library, which interfaces with the Tesseract OCR engine, while OpenCV is used for image processing and visualization.

## Usage  
The script reads an image, detects text using Tesseract OCR, and highlights the detected text in the image. The recognized text is also printed to the console.  

## Requirements
* Python 3.x
* Tesseract OCR
* OpenCV
* Pytesseract
* Pillow (for image manipulation)

## Installation
1. Tesseract OCR Installation  
Download and install Tesseract OCR from https://github.com/tesseract-ocr/tesseract.  
Set the path to the tesseract.exe file in your script:  

   ```bash
   pytesseract.pytesseract.tesseract_cmd = r'C:\\Program Files\\Tesseract-OCR\\tesseract.exe'

2. Python Packages Installation
Install the required Python packages using pip:  

   ```bash
   pip install opencv-python pytesseract pillow


## Configuration
* Page Segmentation Mode (PSM): Determines how Tesseract splits the image into text. The default is set to 3 (Fully automatic page segmentation).
* OCR Engine Mode (OEM): Specifies the OCR engine to use. The default is set to 3 (Legacy + LSTM engines).


> **Note:**
> I was able to create the following application by following the Tutorial created by NeuralNine on Youtube. Here is a link for the tutorial for anyone interested: https://youtu.be/PY_N1XdFp4w?si=FD3UEbBrWPXYE23R
