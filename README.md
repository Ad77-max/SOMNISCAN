# SOMNISCAN
SomniScan is an AI-based drowsiness detection system designed to reduce road accidents caused by driver fatigue. The system uses Python and computer vision techniques to analyze eye movements, blink rate, and facial landmarks in real-time. When signs of drowsiness are detected, the system triggers an alarm alerting the user. 

SomniScan: AI-Powered Drowsiness Detection System

SomniScan is a Python-based real-time drowsiness detection model that uses computer vision and facial landmark analysis to detect early signs of fatigue. The system works through webcam input and alerts the user when drowsiness is detected, helping prevent accidents.

🚀 Features

Real-time face and eye tracking

Eye Aspect Ratio (EAR) calculation

Blink detection and fatigue monitoring

Drowsiness alert using alarm sound

Lightweight, fast, and easy to run


🔧 Setup Instructions

Download the shape_predictor_68_face_landmarks.dat file from:
http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2

Extract and place it in the project root folder

Install dependencies:

pip install -r requirements.txt


Run the project:

python drowsiness_detector.py

🧠 How It Works

SomniScan uses the Eye Aspect Ratio (EAR) principle and 68-point facial landmark detection to measure eye openness.
If EAR falls below a threshold for a certain number of frames → drowsiness warning is triggered.

📦 Technologies Used

Python

OpenCV

dlib

NumPy

imutils

Machine Learning + Computer Vision logic

📈 Applications

Driver fatigue detection

Employee fatigue monitoring

Healthcare monitoring

Smart vehicle systems

Safety and surveillance

🛡️ Future Improvements

Deep learning-based eye-state classifier

Mobile app integration

Dashboard for real-time tracking

Detection in low-light environments
