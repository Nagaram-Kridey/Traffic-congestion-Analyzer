# Traffic-congestion-Analyzer

# 🚗 Real-Time Object Detection for Autonomous Vehicles using YOLOv3

This project implements a **real-time object detection system** using **YOLOv3** (You Only Look Once v3) for identifying vehicles, pedestrians, and road signs in video streams — a key capability for autonomous vehicles.

## Features
- Detects objects like **cars, trucks, pedestrians, traffic signs** in real time
- Processes both **live webcam** and **pre-recorded video**
- Uses **YOLOv3** with **OpenCV** for fast frame-by-frame inference
- Performs **Non-Maximum Suppression (NMS)** to improve detection quality
- Displays bounding boxes and class labels on the video feed

## Tech Stack
- **Python 3.x**
- **OpenCV** (cv2.dnn module)
- **NumPy**
- **YOLOv3** pre-trained model
- **COCO dataset** labels


## Project Structure
yolo-autonomous-detection/
├── yolov3.cfg # YOLOv3 model config
├── yolov3.weights # Pre-trained model weights
├── coco.names # Class labels
├── object_detection.py# Main detection script
└── input_video.mp4 # (Optional) Sample video


## 🚀 Getting Started

## 1. Install Dependencies

pip install opencv-python numpy
## 2. Download Model Files

yolov3.weights
yolov3.cfg
coco.names

## 3. Running the Project

Using a Video File
python object_detection.py
Using Webcam (Edit object_detection.py)
cap = cv2.VideoCapture(0)

## 4. Learning Outcomes
Implement object detection with YOLOv3
Understand CNN-based object localization
Perform frame-by-frame inference in real time
Integrate OpenCV with deep learning models

## 5. References
YOLOv3 Paper
Darknet YOLO Website
OpenCV DNN Module Docs

## 6. Future Improvements
Upgrade to YOLOv5 / YOLO-NAS for better speed and accuracy
Add GPU acceleration with CUDA
Integrate with autonomous vehicle simulators

