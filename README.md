# Web_Application_YOLOv5_Visual_Defect_Detection
Web_Application_YOLOv5_Visual_Defect_Detection

YOLOv5 Image Defect Detector
This project provides a simple web application for detecting defects in images using a trained YOLOv5 computer vision model.

Files
app.py
This file contains the Flask web application code for the image defect detector. It handles image uploads and displays the results of the YOLOv5 model.

result.html
This file contains the HTML and CSS code for displaying the results of the image defect detector. It provides a simple interface for viewing detected defects and downloading the corresponding images.

upload.html
This file contains the HTML and CSS code for uploading images to the image defect detector. It allows users to select multiple images and displays previews of the uploaded images.

Usage
To use the YOLOv5 Image Defect Detector, first ensure that you have installed the required packages by running 
python -m pip install flask
pip install -r requirements.txt

make sure to have python downloaded and installed

Then, run the application with python app.py.

Navigate to localhost:5000 in your web browser to access the web application.

To use the image defect detector, follow these steps:

Click on the "Choose Files" button in the "Upload Image" section to select the images you want to upload.
Click on the "Detect" button to process the uploaded images.
The results of the detection will be displayed on the web page. You can download the detected images by clicking on the "Download" button under each image.

If you wish to change the Ai model, import the yolov5.pt of your choice. For example yolov5_230518.pt is the Ai model file you would like to use, then import it to YOLOV5 folder and change the already existing yolov5.pt to yolov5_230518.pt in the detect.py file.