# clean-ocr
Open image -> draw over zone of interest (drag&drop) -> get text.

Sometimes you just don't need to scan the whole image. </br>
And cut it into another file is a bit annoying. </br>
So use this script. </br>

## Installation
1 - Download the whole project </br>
2 - Open the terminal at the project's folder </br>
3 - run ```pip install -r requirements.txt``` </br>
4 - **important, you need to install Tesseract OCR as well, see below** </br>

## Usage
5 - run ```python clean-ocr.py $path_to_your_image_here``` </br>
example -> ```python clean-ocr.py C:\users\image.jpg``` </br>
6 - After your image is loaded, drag and drop forming as many rectangles as you like, selecting the zones of interest </br>
7 - And just press enter! </br>

ESCAPE KEY &nbsp; &nbsp; &nbsp; &nbsp;-> close </br>
ENTER KEY &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;-> get text from selected areas </br>
BACKSPACE KEY  &nbsp; -> start again</br>

![alt text](https://github.com/MauBorre/clean-ocr/blob/main/example.png?raw=true)

# Uses Tesseract OCR 
Project: https://github.com/tesseract-ocr/tesseract </br>
Windows installer: https://github.com/UB-Mannheim/tesseract/wiki </br>
Other installation methods: https://tesseract-ocr.github.io/tessdoc/Installation.html </br>

