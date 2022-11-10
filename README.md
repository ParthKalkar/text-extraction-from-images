# text-extraction-from-imge
In this project, we will be working on extracting text from images. After extracting the text we will apply some basic function of `openCV` on that text to enhance it and to get more accurate results. 

This project will be very useful as it will save time and effort of typing from an image.
## Scope
DIfferent organizations can use this to extract useful information from the image and store it. Individuals can use it for saving their time and effort for typing. 

It will ease the burden of document analysis and understanding them. It will reduce man work and revolutionize the system by automating the OCR method for text extraction. 

## Steps
1. Downloading Tesseract and install it with other dependencies. 
2. Loading the image for text extraction, resizing it and then save it.
3. Using Pytesseract to extract the text from the image.
4. Processing the text extracted from the image.
5. Using Computer Vision for further processing of complex images.
6. Removing noise from the image using the blue function.
7. Perfrom threshold transformation of the image.
8. Using Erode function of CV2 on image.
9. Performing some other image processing operations.
10. Drawing rectangles around a character and a particular pattern/word.

## Technology
1. Python
2. OpenCV
3. PyTesseract
4. Flask

## Input Image
![image](https://user-images.githubusercontent.com/50231750/201101159-820c11f4-389b-4098-994c-f17b742833bf.png)

## Input Text
BOLD

## Output
![image](https://user-images.githubusercontent.com/50231750/201101645-14a4c738-4a1b-4177-a84d-191263a3b677.png)

## Conclusion
We started with learning how to install tesseract which is the used for text extraction. Next we took an image and extracted the text from that image. We learned that we need to use certain image transformation function of OpenCV in order to extract text from complex images.
