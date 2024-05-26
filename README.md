
# PDF to Word Converter with OCR

This Python script converts a PDF file to Word format using OCR (Optical Character Recognition). It extracts text from each page of the PDF, converts the pages to images, performs OCR on the images, and saves the extracted text to text files.

## Features

- Extracts text from each page of a PDF file
- Converts PDF pages to images for OCR
- Performs OCR using Tesseract
- Saves extracted text to text files

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/Sweatnessstrong/pdf-to-word-converter.git
   ```

2. Install the required libraries:
   ```
   pip install PyPDF2 pytesseract pdf2image
   ```

3. Set the path to the Tesseract executable in the script:
   ```python
   pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'
   ```

## Usage

1. Place your PDF file in the project directory.
2. Run the script:
   ```
   python pdf_to_word_converter.py
   ```

## Dependencies

- PyPDF2
- pytesseract
- pdf2image

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature`)
6. Create a new Pull Request
