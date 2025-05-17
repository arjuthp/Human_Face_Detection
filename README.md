"# Human_face_detection" 

What is this?

This project detects human faces in images and webcam video. It uses HOG (Histogram of Oriented Gradients) to find image patterns and SVM (Support Vector Machine) to check if they’re faces. Haar Cascade helps spot faces quickly in video.

What it does





Labels images as "face" or "non-face" and saves them.



Finds HOG patterns in images for face detection.



Trains SVM to recognize faces.



Shows faces in webcam video with green boxes.

Files





image_processing.py: Labels and saves images.



image_classification.py: Creates hog_features.pkl with HOG patterns.



face_detection.py: Trains SVM and runs webcam face detection.



hog_features.pkl: Stores HOG patterns and labels.



README.md: This file.



venv: Python virtual environment.

Tools Needed





Python 3



OpenCV



NumPy



scikit-image



scikit-learn



Pickle

