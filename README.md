# Project-FrameAnalyser
🖼️ Real-Time Object & Keypoint Detection System
🔍 Powered by YOLO | 👁️ Eye–Ear Keypoint Tracking | 🚨 Presence Alert System

This project is a real-time object detection and keypoint-based monitoring system built using YOLO (You Only Look Once).
Along with standard object detection, it includes advanced head–facial keypoint tracking and an automatic alarm system when a person leaves the camera view.

🚀 Features
✅ 1. Real-Time Object Detection

Detects multiple objects instantly using YOLO.

Efficient & lightweight code for high FPS performance.

Works on both webcam and video input.

👁️ 2. Advanced Keypoint Detection

Using YOLO Pose Keypoints, the system tracks:

Right Eye

Left Eye

Nose

Right Ear

Left Ear

These keypoints help analyze human presence, direction, and reliability.

🚨 3. Presence Alert System

If the person’s head disappears from the screen (i.e., keypoints not detected), the system triggers:

🔔 Beep sound / Alarm

Helps in live monitoring and automation tasks

🧠 4. Multi-Purpose Use Cases
🛡️ Surveillance Systems

Airports, malls, hospitals, public spaces

Detect suspicious activity and objects

📝 Exam Monitoring

Alarm when a student moves out of frame

Helps detect malpractice or absence

🏥 Early Disease/Health Monitoring

Eye–ear asymmetry detection can be extended for:

Paralysis early signs

Drowsiness detection

Head-position abnormalities

🎯 General Computer Vision Tasks

Can be integrated with gesture recognition

**📁 Project Structure**

Your folder contains the following files:

├── object_detection_project.ipynb    # Main notebook for detection

├── knock1.jpg                        # Test image 1

├── football.jpg                      # Test image 2

├── hello.jpeg                        # Test image 3

├── yolov8n-pose.pt (or similar)      # YOLO pose model file

├── README.md                         # Documentation (this file)

**🛠️ Tech Stack**

Python

OpenCV

Ultralytics YOLOv8

NumPy

playsound (for alarm sound)

Jupyter Notebook (project written in .ipynb)

**▶️ How to Run**

1️⃣ Install Libraries
pip install ultralytics opencv-python numpy playsound

2️⃣ Open the Notebook
jupyter notebook object_detection_project.ipynb

3️⃣ Run All Cells

The YOLO model loads

Keypoint detection starts

Alarm activates when person disappears

**🔮 Future Improvements**

Add GUI for user-friendly interface

Add attendance system using face recognition

Add logs of alerts (time-stamped)

Cloud or web-based monitoring dashboard

Integrate multiple camera feeds

**⭐ Support**

If this project helped you, please star ⭐ the repository!

Can be used for smart classrooms

Can be part of robotics and automation
