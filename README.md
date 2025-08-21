# Autonomous Number Plate Recognition using YOLO in Python

## Overview
This project implements an Autonomous Number Plate Recognition (ANPR) system using YOLO (You Only Look Once) for object detection in Python. The system is designed to detect and recognize license plates in images and video streams, providing a valuable tool for automated vehicle surveillance, toll collection systems, parking management, and other applications requiring vehicle identification.

## Features
* Object detection: Utilizes YOLOv3 (or YOLOv4) for real-time object detection to locate vehicles and license plates within images or video frames.
License plate recognition: Extracts and recognizes license plate characters using Optical Character Recognition (OCR) techniques.
* Real-time processing: Provides real-time processing capabilities for video streams, allowing for continuous monitoring and analysis.
* Configurable: Offers configuration options to adjust detection thresholds, image preprocessing techniques, and OCR settings for optimal performance in different environments.

## Installation

* Clone this repository to your local machine
* Install dependencies using pip:
  - pip install -r requirements.txt
* Navigate to the project directory:
  - cd ANPR-YOLO-Python
* Run the ANPR system on an image or video file:
  - python anpr.py --input input_file.jpg
    
    OR
  - python anpr.py --input input_file.mp4


## Credits
- YOLOv3 (or YOLOv4) for object detection
- OpenCV for image processing
- Tesseract OCR for license plate recognition
