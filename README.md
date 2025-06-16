🛑 Driver Drowsiness Detection System
The Driver Drowsiness Detection System is an AI-powered safety application that monitors a driver’s eye and facial behavior in real-time to detect signs of fatigue or sleepiness. The system helps reduce road accidents caused by drowsy driving by triggering alerts before a critical situation occurs.

🔍 Overview
Every year, thousands of accidents happen due to driver fatigue. This system aims to prevent such incidents by detecting drowsiness using a webcam and alerting the driver through visual and audio signals.

📸 Key Features
👁️ Real-time Eye & Face Detection using OpenCV and Haar Cascades/Dlib

😴 Drowsiness Detection based on Eye Aspect Ratio (EAR)

🔊 Instant Audio Alerts (Buzzer/Sound) on drowsiness detection

🧠 Facial Landmark Detection using dlib or mediapipe

🧪 Live Video Feed Interface

💻 Lightweight and runs on standard hardware

🧰 Tech Stack
Technology	Description
Python	Main programming language
OpenCV	Image processing and video streaming
Dlib / Mediapipe	Facial landmark detection
Pygame / Playsound	For playing alert sounds
NumPy	Array and mathematical operations


⚙️ How It Works
Captures live video using the webcam.

Detects the driver’s face and eyes.

Calculates the Eye Aspect Ratio (EAR).

If EAR remains below a threshold for a certain duration:

Plays an alert sound

Displays a visual warning on screen

📈 EAR Formula
EAR = (||p2 - p6|| + ||p3 - p5||) / (2 * ||p1 - p4||)

A low EAR value indicates closed eyes.

🛠 Requirements
Python 3.6+

Webcam

Packages:

opencv-python

dlib or mediapipe

imutils

numpy

playsound or pygame

🚧 Future Enhancements
🔋 Mobile App Version (Android/iOS)

🌐 Integration with Car Infotainment Systems

📉 Fatigue Prediction using Machine Learning Models

🚗 Vehicle Speed and Lane Monitoring

👨‍💻 Author
Nitanshu Chaudhry

Feel free to connect on LinkedIn or contribute to improve this project!
