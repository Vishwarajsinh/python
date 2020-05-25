For Windows Only:

1 - You need to have Tesseract OCR installed on your computer.

get it from here: https://github.com/UB-Mannheim/tesseract/wiki

Download the suitable version.

2 - Add Tesseract path to your System Environment. i.e. Edit system variables.

3 - Run pip install pytesseract and pip install tesseract

4 - Add this line to your python script every time

pytesseract.pytesseract.tesseract_cmd = 'C:/OCR/Tesseract-OCR/tesseract.exe'  # your path may be different

5 - Run the code.
