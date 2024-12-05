# Extract Images from PDF using Python Tkinter
________________________________________
## Description:
This project is a user-friendly desktop application built with Python and Tkinter that allows users to extract images embedded within PDF files. The primary goal of the project is to simplify the process of retrieving and saving images from PDF documents in an intuitive graphical interface.
________________________________________
## Key Features:

## 1)	File Selection:

Users can browse and select a PDF file from their system using a file dialog.

## 2)	Image Extraction:

 The application utilizes libraries like pikepdf to extract high-quality images embedded in the selected PDF document.
 
## 3)	Preview Capability:

A preview section allows users to view extracted images before saving them to the local directory.

## 4)	Custom Save Options:

a) Users can choose the format for saving the images (e.g., PNG, JPEG).

b) Option to select a destination folder for saving the images.

## 5)	Progress Indicator:

A progress bar or status label provides feedback during the extraction and saving process.

## 6)	Error Handling:

The application gracefully handles errors, such as unsupported PDFs, missing images, or invalid file paths, and displays appropriate messages.
________________________________________
## Technical Implementation:

1)	User Interface (UI):
2)	
a)	Designed using Tkinter for a clean and straightforward layout.

b)  Includes buttons for file selection, image preview, and save actions.

## 2)	Backend Logic:

a) 	PDF Processing: Uses pdf  to parse the PDF and locate images.

b) 	Image Conversion: Ensures extracted images are properly converted to standard formats using libraries like pdfImage

## 3) 	Directory and File Handling:

Incorporates Python's built-in os  libraries to manage file paths and directories efficiently.
________________________________________
## Benefits:

a)	Enables users without programming expertise to extract images from PDFs quickly.

b)	Useful for researchers, students, and professionals who need to analyze or reuse visual content in PDFs.

![extract_image](https://github.com/user-attachments/assets/4383d501-443d-411e-ba25-c1db45f52c0b)

