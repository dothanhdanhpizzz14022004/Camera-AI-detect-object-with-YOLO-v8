Download 3 Files

- [coco.names](https://github.com/pjreddie/darknet/blob/master/data/coco.names)
- [yolov3.cfg](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)
- [yolov3.weights](https://pjreddie.com/media/files/yolov3.weights)
# AI Object Detection Camera System
Click to watch demo: [Video ](https://youtu.be/7piaPqYl4Fc)
A real-time object detection system that combines **ESP32-S3-CAM** for live video streaming with **YOLO** model for intelligent object detection on a host computer.

## Project Overview

This project demonstrates a hybrid Embedded + AI solution:
- **ESP32-CAM** acts as a wireless camera streaming live video over Wi-Fi.
- A **Python application** receives the video stream and performs real-time object detection using **YOLO**.

## Features

- Live MJPEG video streaming from ESP32-CAM
- Real-time object detection with bounding boxes and confidence scores
- Support for multiple object classes (COCO dataset)
- Adjustable detection confidence threshold
- Wi-Fi Access Point and Station mode support
- Easy-to-use Python interface with OpenCV visualization

## Hardware Requirements

- **ESP32-S3-CAM** module
- Host computer (Windows/Linux/Mac) for running YOLO detection

## Project Structure
Camera-AI-detect-object-with-YOLO-v8/
├── Sketch_32.1_CameraWebServer/              # ESP32 firmware (Arduino)
│   ├── Sketch_32.1_CameraWebServer.ino
│   └── ...
├── python/                 # Host computer application
│   ├── detect.py           # Main detection script
│   └── ...
└── README.md
