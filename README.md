# 🚗 License Plate Recognition using YOLO and CNN

This project implements a **real-time license plate detection and recognition system** using **YOLO (You Only Look Once)** for object detection and **CNN (Convolutional Neural Network)** for character recognition.  
It is designed to automatically detect license plates from images or video streams and read the alphanumeric characters accurately.

---

## ✨ Features
- Real-time **license plate detection** with YOLO.
- **Character segmentation and recognition** using CNN.
- Handles multiple license plates in a single image.
- Works with images and live video feeds.
- **Preprocessing and normalization** for accurate recognition.
- Lightweight and fast for practical applications.

---

## 🛠️ Tech Stack
- Python 3.x
- OpenCV (`pip install opencv-python`)
- TensorFlow / Keras (`pip install tensorflow`)
- YOLOv5 or YOLOv8 model for license plate detection
- Numpy, Matplotlib for data handling and visualization

---

## How It Works
1. **Detection Stage**:
   - YOLO model detects license plate bounding boxes in the input image or video.
2. **Segmentation Stage**:
   - The detected plate is cropped and segmented into individual characters.
3. **Recognition Stage**:
   - A CNN model predicts each character from the segmented image.
4. **Output**:
   - The complete license plate number is reconstructed and displayed on the screen.

---

## 🔧 Features & Advantages
- Real-time detection and recognition.
- High accuracy due to deep learning-based models.
- Can be extended to multiple license plate formats.
- Easily integrable with traffic monitoring or parking systems.

---

Automate license plate recognition efficiently using **YOLO + CNN** for fast and accurate results!
