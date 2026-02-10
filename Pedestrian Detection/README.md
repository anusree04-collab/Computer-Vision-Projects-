# Pedestrian Detection (Full Body) from Video using OpenCV 

This project performs *pedestrian (full-body) detection from a video* using *OpenCV’s HOG (Histogram of Oriented Gradients) descriptor with SVM*.

The system detects human full bodies frame-by-frame and draws bounding boxes around detected pedestrians.

---

##  Project Overview
- Detects pedestrians (full human body) from video input
- Uses HOG descriptor with a pre-trained SVM model
- Works on recorded video files or webcam feed
- Draws bounding boxes around detected pedestrians

---

##  Technologies Used
- Python
- OpenCV
- HOG Descriptor
- Support Vector Machine (SVM)
- Computer Vision (AI)

---

##  Files Used
- pedestrian_detection.py – main Python script
- input_video.mp4 – video used for pedestrian detection

> HOG + SVM model is provided by OpenCV.

---

##  How It Works
1. Reads video frames one by one
2. Converts frames to grayscale
3. Applies HOG descriptor for feature extraction
4. Uses SVM classifier to detect pedestrians
5. Draws bounding boxes around detected pedestrians
6. Displays the output video in real time

---
