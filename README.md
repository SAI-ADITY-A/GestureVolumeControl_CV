# HandTrackingProject---CV

This project is a gesture recognition application that allows you to control the system volume by detecting hand gestures using a webcam. Leveraging OpenCV and MediaPipe, the project detects hand landmarks and interprets gestures to adjust the volume level dynamically.

## Features
- Real-Time Hand Tracking: Uses OpenCV and MediaPipe to track and visualize hand landmarks.
- Gesture-Based Volume Control: Detects specific hand gestures to increase or decrease the system volume.
- Efficient and Lightweight: Utilizes MediaPipe’s efficient hand tracking for accurate and fast gesture recognition.

## Demo
![image](https://github.com/user-attachments/assets/3540f16e-1e10-4f5d-a3b6-8768554bb441)

## Requirements
- Python 3.8+
- OpenCV
- MediaPipe
- Pycaw (for controlling system audio on Windows)

Install the required libraries
To install all dependencies, use:
``` bash
pip install opencv-python mediapipe pycaw
```

## Code Explanation
### HandTrackingModule.py: 
Contains a handDetector class, which uses MediaPipe’s hand landmarks to detect and track hands in real time.
### VolumeHandControl.py: 
Utilizes the handDetector to interpret hand gestures and modify the system’s volume using the Pycaw library.


