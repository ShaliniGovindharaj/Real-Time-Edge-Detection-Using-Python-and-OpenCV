# Real-Time Edge Detection Using Python and OpenCV

## 📌 Project Overview

This project demonstrates **real-time edge detection** using a webcam and the **Canny Edge Detection** algorithm in OpenCV. The live video stream is captured from the system camera, converted into grayscale, and processed to detect edges frame by frame.

This project is ideal for beginners to understand **computer vision basics**, image processing, and real-time video handling in Python.

---

## 🎯 Objectives

* Capture live video using a webcam
* Convert color frames to grayscale
* Detect edges using the Canny algorithm
* Display processed frames in real time

---

## 🛠️ Technologies Used

* **Python 3**
* **OpenCV (cv2)**

---

## ⚙️ Requirements

Install OpenCV if not already installed:

```bash
pip install opencv-python
```

---

## ▶️ How to Run the Project

1. Save the code as `edge_detection.py`
2. Open terminal / command prompt
3. Run the command:

```bash
python edge_detection.py
```

4. Press **Q** to exit the window

---

## 🧠 Algorithm

1. Initialize webcam using `cv2.VideoCapture(0)`
2. Read frames continuously inside a loop
3. Convert each frame to grayscale
4. Apply Canny edge detection
5. Display the detected edges
6. Stop execution when the user presses **Q**

---

## 📸 Output Description

* Webcam window opens
* Live edges of objects are highlighted in white
* Background remains black

---

## 🚀 Applications

* Computer vision learning
* Object boundary detection
* Preprocessing for image analysis
* Robotics and automation

