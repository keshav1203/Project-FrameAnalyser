<div style="background-color:#1a1a1a; color:white; padding:25px; border-radius:12px; text-align:center;">
  <h1>🖼️ Real-Time Object Detection & Keypoint Alert System</h1>
  <p style="font-size:16px;">
    YOLO-based object detection | Facial keypoints tracking | Presence monitoring with sound alert
  </p>
</div>

---

## 🔍 **Project Overview**

This project is a **real-time object detection and keypoint-based monitoring system** using **YOLO**.  
It detects objects, identifies **eyes, ears, and nose**, and triggers an **alarm sound** using `playsound`  
when a person disappears from the camera frame.

---

<div style="background-color:#2d2d2d; color:white; padding:15px; border-radius:8px;">
<b>🔥 Key Features</b>
</div>

### ✅ **Real-Time Object Detection**
- High accuracy  
- Runs on webcam or video  
- Supports any YOLOv8 model  

### 👁️ **Keypoint Tracking**
Detects the following in real-time:
- Left Eye  
- Right Eye  
- Nose  
- Left Ear  
- Right Ear  

### 🚨 **Alert Using `playsound`**
If no person is detected:
- A loud **beep sound plays automatically**  
- Great for monitoring & security

---

<div style="background-color:#2d2d2d; color:white; padding:15px; border-radius:8px;">
<b>📁 Project Structure</b>
</div>
├── object_detection_project.ipynb
├── knock1.jpg
├── football.jpg
├── hello.jpeg
├── yolov8n-pose.pt (or similar YOLO model)
└── README.md

---

## 🧠 **Use Cases**

<div style="background-color:#eeeeee; padding:10px; border-radius:6px;">
<b>💡 Surveillance</b> – Airports, malls, public spaces  
<br>
<b>💡 Exam Monitoring</b> – Alert when a student leaves the frame  
<br>
<b>💡 Health Detection</b> – Early signs of drowsiness or facial deviation  
</div>

---

## 🛠️ **Tech Stack**

- Python  
- OpenCV  
- Ultralytics YOLOv8  
- NumPy  
- playsound  
- Jupyter Notebook  

---

## ▶️ **How to Run**

1️⃣ Install the requirements  
```bash
pip install ultralytics opencv-python numpy playsound

2️⃣ Open the Jupyter Notebook
jupyter notebook object_detection_project.ipynb

3️⃣ Run all cells

YOLO model loads

Webcam detection begins

Alarm triggers if person disappears

---

**🔮 Future Improvements**

Add GUI dashboard

Add face recognition

Add timestamped logs when alarm rings

Multi-camera support

Cloud-based monitoring

⭐ **Support**

If this project helped you, please star ⭐ the repository.
It encourages future development!
