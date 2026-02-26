Real-Time Color Detection using OpenCV

 Overview

This project implements a real-time color detection system using OpenCV.  
It captures live video from a webcam and applies color masking techniques to detect and highlight specific colors in the frame.

The system can detect:

- 🔴 Red Color Mask  
- 🔵 Blue Color Mask  
- 🟢 Green Color Mask  
- 🎯 All colors except white  

This project demonstrates fundamental Computer Vision concepts such as color space conversion and masking.

---

 Objective

Build a real-time video processing application that detects and isolates specific colors using HSV color thresholding.

---

Key Concepts Used

- OpenCV
- HSV (Hue, Saturation, Value) Color Space
- Color Thresholding
- Masking
- Bitwise Operations
- Real-Time Video Capture

---

 How It Works

1. Capture live video using webcam.
2. Convert frame from BGR to HSV color space.
3. Define lower and upper HSV bounds for each color.
4. Create masks using cv2.inRange().
5. Apply bitwise operations to extract colored regions.
6. Display masked output in real time.

---

Technologies Used

- Python
- OpenCV
- NumPy

---

---

 How to Run the Project

 Install Dependencies


pip install opencv-python numpy


 Run the Script

bash
python detect.py


 Webcam Window Opens

Press q to exit the application.

---

 Output

- Live webcam feed
- Red color masked output
- Blue color masked output
- Green color masked output
- Mask showing all colors except white

---

 Example Use Cases

- Object tracking
- Robotics vision systems
- Traffic signal detection
- Industrial color-based sorting
- Basic surveillance systems


---

## 📚 Domain

Computer Vision | Image Processing | OpenCV | Real-Time Video Analytics
