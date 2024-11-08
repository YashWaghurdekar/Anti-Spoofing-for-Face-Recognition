# Anti-Spoofing for Face Recognition | Machine Learning

This project implements a robust anti-spoofing system for face recognition, specifically designed for applications such as school attendance and online exams. Leveraging OpenCV (cv2) and YOLOv8 for real-time face detection and recognition, this system distinguishes between live subjects and spoofing attempts like images or videos. The model achieved an accuracy of 90% in detecting spoofing attacks, greatly enhancing the security and reliability of face recognition systems.

## Features
- **Real-time Detection:** Real-time face detection and recognition using YOLOv8 and OpenCV.
- **Anti-Spoofing Techniques:** Distinguishes between live faces and spoofing attempts.
- **Custom Dataset:** Uses a custom dataset for improved training and evaluation.
- **High Accuracy:** Attains 90% accuracy in detecting spoofing attempts.

## Code Files

### 1. `main.py`
Handles real-time face detection using YOLO and OpenCV. The script applies bounding boxes and confidence levels for live or fake face classification.

### 2. `datacollection.py`
Collects face data for training purposes. Detects faces, checks blur levels, and saves images and labels to a dataset for training.

### 3. `facedetector_test.py`
Tests face detection capabilities. Displays the bounding box and center of the detected face on a live feed.

### 4. `textfiletest.py`
Demonstrates simple file handling by writing a line of text to a file.

### 5. `train.py`
Trains the YOLO model on the custom dataset with specified parameters. This script is essential for creating a model that can recognize spoofing attempts effectively.

### 6. `yolotest.py`
Tests the YOLO model on a video feed or video file, displaying detected objects with bounding boxes and confidence scores.

## Getting Started

### Prerequisites
- Python 3.x
- Required packages: `opencv-python`, `ultralytics`, `cvzone`

## Sample Output
| Real Face Detection | Spoof Detection |
|----------------------|-----------------|
| ![Real Face](https://github.com/YashWaghurdekar/Anti-Spoofing-for-Face-Recognition/blob/8d1bdf49cf02b6adbf7ce37e459b4835db68169b/real_face_sample.jpeg) | ![Spoof Face]() |


