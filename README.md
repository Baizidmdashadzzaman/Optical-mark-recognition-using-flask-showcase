# Project Description: OMR Checker Using OpenCV, Image Processing, NumPy, and Flask

![image](Capture.PNG?raw=true "Nuxt JS Portfolio for developer")
### <a href="https://www.youtube.com/watch?v=Xkx2GZTYD0s">LIVE DEMO</a>

Overview:
The OMR (Optical Mark Recognition) Checker is a web-based application designed to automatically evaluate student answer sheets in real-time using a webcam. The application leverages OpenCV for image processing, NumPy for numerical operations, and Flask to provide a user-friendly web interface. This system aims to simplify and speed up the process of checking multiple-choice answer sheets by automating the evaluation process.

Features
Real-time Image Capture: Uses a webcam to capture images of the answer sheets.
Image Preprocessing: Applies image processing techniques such as thresholding, noise reduction, and contour detection to prepare the image for analysis.
OMR Detection: Identifies and interprets marked bubbles on the answer sheets using OpenCV and NumPy.
Score Calculation: Compares the detected marks against an answer key to calculate scores.
Web Interface: Provides an easy-to-use interface built with Flask for uploading answer keys, viewing results, and managing the process.
Data Storage: Stores results and answer keys for future reference and analysis.
Technical Details
OpenCV for Image Processing:

Thresholding: Converts captured images to binary format for better bubble detection.
Contour Detection: Identifies the marked regions (bubbles) on the OMR sheet.
Perspective Transform: Corrects any skew or orientation issues in the captured image.
NumPy for Numerical Operations:

Efficient handling of image matrices.
Calculation of marked responses by analyzing pixel values.
Flask for Web Interface:

Routes for uploading answer keys and captured images.
Endpoints for processing images and returning results.
HTML templates for displaying scores and detailed reports.
Workflow
Initialization:

Start the Flask server.
Access the web application via a browser.
Answer Key Upload:

Upload the correct answers for the OMR sheet via the web interface.
Capture and Process OMR Sheets:

Use the webcam to capture an image of the student's answer sheet.
The image is processed to detect marked bubbles.
Score Calculation:

The system compares detected marks with the answer key.
Scores are calculated and displayed on the web interface.
Results and Analysis:

View detailed results, including correct and incorrect responses.
Option to save or print the results for record-keeping.
Benefits
Efficiency: Significantly reduces the time required to check and score multiple-choice exams.
Accuracy: Minimizes human error in the evaluation process.
Real-time Processing: Immediate feedback on student performance.
User-Friendly Interface: Easy to navigate and operate, even for users with minimal technical knowledge.
Conclusion
The OMR Checker using OpenCV, NumPy, and Flask is a powerful tool designed to streamline the evaluation of multiple-choice exams. By integrating real-time image processing with a web-based interface, it offers a practical solution for educational institutions to handle large volumes of answer sheets efficiently and accurately.

