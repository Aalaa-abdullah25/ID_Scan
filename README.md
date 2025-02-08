# Business Card Scanner

## Overview

This project is a Business Card Scanner application that uses OCR (Optical Character Recognition) to extract text from images of business cards. The application is built using Python, Streamlit, OpenCV, and Tesseract OCR.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd Project1
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure Tesseract OCR is installed on your system. You can download it from [here](https://github.com/tesseract-ocr/tesseract).
2. Update the `pytesseract.pytesseract.tesseract_cmd` path in the `ID_com_scanner.py` file to point to your Tesseract installation directory.
3. Run the Streamlit application:
   ```bash
   streamlit run ID_com_scanner.py
   ```
4. Upload an image of a business card using the file uploader in the web interface.
5. The application will display the uploaded image and extract text from it.

## Files

- `ID_com_scanner.py`: The main application file.
- `requirements.txt`: Contains the list of dependencies required for the project.
- `Business Card Scanner.ipynb`: Jupyter notebook with installation and setup instructions.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [OpenCV](https://opencv.org/)
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
