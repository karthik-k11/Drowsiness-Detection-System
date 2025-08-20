# 💤 Drowsiness Detection System

The **Drowsiness Detection System** is an AI-powered computer vision project that helps prevent accidents caused by driver fatigue. It uses **OpenCV**, **Dlib**, and **Machine Learning** techniques to monitor eye movements and alert the user when signs of drowsiness are detected.

## 🚀 Features
- Real-time face and eye detection using OpenCV.
- Eye Aspect Ratio (EAR) calculation to detect eye closure.
- Alerts the user when drowsiness is detected.
- Lightweight and works on standard webcams.
- Can be extended for vehicle safety systems.

## 🛠️ Technologies Used
- Python  
- OpenCV  
- Dlib  
- Imutils  
- Numpy  

## 📐 EAR Formula

$$
EAR = \frac{ \|p_2 - p_6\| + \|p_3 - p_5\| }{ 2 \times \|p_1 - p_4\| }
$$

**Where:**
- `p1 ... p6` → 6 eye landmark points  
- `|pi - pj|` → Euclidean distance between two points  
- If **EAR < 0.25** for **N consecutive frames** → drowsiness alert is triggered


## 📌 Project Highlights
- Detects driver drowsiness by monitoring eye blink patterns.  
- Provides real-time feedback with alarms.  
- Helps improve road safety.  

## 📂 Future Enhancements
- Add yawning detection for more accurate monitoring.  
- Integrate with IoT devices for automatic vehicle control.  
- Develop a mobile application version.  

