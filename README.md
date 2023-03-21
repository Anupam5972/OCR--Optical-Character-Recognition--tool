# OCR Image-to-Text Converter
This Python script takes an image file with text content, converts it to text using Optical Character Recognition (OCR) technology and saves the text in a text file with the same name as the original image file but with '_Text' appended.

The script uses the pytesseract library to perform OCR on the image file and the PIL (Python Imaging Library) to open the image. The script creates a folder named 'text_files' in the same directory as the original image, if it does not already exist. The text output is saved in a new text file in the 'text_files' folder.

To use this script, ensure that you have installed the necessary libraries: pytesseract and PIL. Also, make sure that the path to the image file is correct. Run the script and the OCR output will be saved in the 'text_files' folder in the same directory as the image.

Image: 

![image](https://user-images.githubusercontent.com/86146673/226641099-3e4d18e0-a93c-456b-8b68-387b723ef581.png)

This OCR Image-to-Text Converter is useful for converting text from images to text that can be easily edited or processed in other applications.

Output:

![image](https://user-images.githubusercontent.com/86146673/226641226-01f50c28-7461-47f6-affe-a188e93598e0.png)
