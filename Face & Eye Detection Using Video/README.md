# Face Detection using OpenCV 

This project implements *real-time face detection* using a webcam and *Haar Cascade Classifier* in OpenCV.

The system detects human faces from live video input and draws bounding boxes around detected faces.

---

##  Project Overview
- Uses Haar Cascade XML files for face detection
- Works on live webcam video
- Converts frames to grayscale for efficient detection
- Draws rectangles around detected faces in real time

---

## Technologies Used
- Python
- OpenCV
- Haar Cascade Classifier
- Computer Vision

---

##  Files Used
- face_detection.py – main Python script
- haarcascade_frontalface_default.xml – face detection model

> Note: Haar cascade XML files are pre-trained models provided by OpenCV.

---

##  How It Works
1. Captures video from the webcam
2. Converts each frame to grayscale
3. Detects faces using Haar Cascade classifier
4. Draws bounding boxes around detected faces
5. Displays the output video in real time

---
