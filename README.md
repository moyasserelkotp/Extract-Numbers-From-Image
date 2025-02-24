# Image to Contacts Extractor

This Python project uses Optical Character Recognition (OCR) to extract phone numbers and names from an image and generates both VCF (vCard) and CSV files for contact management. It comes with a simple GUI built using Tkinter for uploading images and downloading the generated files.

## Features
- **OCR Extraction**: Extract phone numbers and names from images using pytesseract.
- **VCF File Generation**: Automatically generate a VCF file to save contacts.
- **CSV File Generation**: Generate a CSV file containing the contact information.
- **Dark Mode UI**: A simple, dark-themed Tkinter GUI for easy interaction.
- **Manual Name Input**: If no name is found in the image, the user is prompted to enter a default name.

## Requirements

- Python 3.x
- Tesseract OCR (installed and configured on your system)

### Python Libraries

- **pytesseract**: Python wrapper for Tesseract OCR.
- **opencv-python**: Library for image processing.
- **vobject**: Python library for handling vCard files.
- **tkinter**: Standard GUI library for Python.
- **csv**: Standard Python library for CSV file handling.

To install the required libraries, you can use the provided `requirements.txt`:

```bash
pip install -r requirements.txt

