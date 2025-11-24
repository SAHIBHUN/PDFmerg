# Image to PDF Converter

## Problem Statement

Many users often have multiple images in different formats (JPG, PNG, BMP, WebP) and need to compile them into a single PDF document. Manually inserting images into a PDF is time-consuming and inefficient. This project aims to automate the conversion of multiple image files into a single PDF, making the process faster and more convenient.

## Scope of the Project

The scope of this project includes:

* Selecting multiple images from the local filesystem.
* Converting all selected images into a single PDF file.
* Handling different image formats including PNG, JPG, JPEG, BMP, and WebP.
* Maintaining image quality in the generated PDF.
* Providing a simple and user-friendly graphical interface for easy usage.

## Target Users

* Students and professionals who need to compile image files into PDF documents.
* Users who frequently work with scanned images or screenshots.
* Anyone looking for a simple, GUI-based solution for image-to-PDF conversion without requiring technical expertise.

## High-Level Features

* **Multi-Image Selection:** Choose multiple image files at once.
* **Supported Formats:** Handles popular image formats like PNG, JPG, JPEG, BMP, and WebP.
* **PDF Conversion:** Combine all selected images into a single PDF file.
* **User-Friendly GUI:** Simple interface built using Tkinter for easy navigation.
* **Error Handling:** Displays messages if no images are selected or if saving fails.
* **Image Mode Handling:** Automatically converts images with transparency to ensure compatibility with PDF format.
