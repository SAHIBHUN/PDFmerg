# PDFmerg
Image to pdf converter 
README – Image to PDF Converter (Python GUI)
 Overview
 This project provides a simple and user-friendly GUI tool to convert one or more image files into a single PDF document. It is built using Python, Tkinter, and Pillow.
 Features- Select multiple images- Combine all images into one PDF- Supports PNG, JPG, JPEG, WEBP, BMP- Handles transparent images- Lightweight UI using Tkinter
 Requirements
 pip install pillow
 Installation
 1. Download or copy this project folder
 2. Ensure image_to_pdf_gui.py is present
 3. Install dependencies
 How to Run
 python image_to_pdf_gui.py
 How to Use
 1. Click Select Images
 2. Choose images
 3. Click Convert to PDF
 4. Choose save location
 How It Works
- Loads images via Pillow
- Converts transparent images to RGB
- Appends images into PDF
 Future Enhancements
- Drag & drop
- Folder conversion
- One PDF per image
- Dark mode
