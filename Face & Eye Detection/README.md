# Face & Eye Detection from Image using OpenCV 

This project performs *face and eye detection on a static image* using *Haar Cascade Classifiers* in OpenCV.

The system first detects faces in the image and then detects eyes *within each detected face region*.

---

##  Project Overview
- Detects faces from an image
- Detects eyes inside detected faces
- Uses Haar Cascade XML files
- Works on static images (not live video)

---

##  Technologies Used
- Python
- OpenCV
- Haar Cascade Classifiers
- Computer Vision (AI)

---

##  Files Used
- face_eye_detection.py – main Python script
- haarcascade_frontalface_default.xml – face detection model
- haarcascade_eye.xml – eye detection model
- input_image.jpg – image used for detection

> Haar Cascade XML files are pre-trained models provided by OpenCV.

---

##  How It Works
1. Reads the input image
2. Converts the image to grayscale
3. Detects faces using Haar Cascade
4. Extracts face regions
5. Detects eyes within each face region
6. Draws bounding boxes around faces and eyes
7. Displays the final output image

---
