# Transfer Learning Using YOLO and VGG16 for Gender Detection

## Overview
This project leverages **YOLOv8** for face detection and a **VGG16-based gender classification model** to determine whether a detected face is male or female. By combining **transfer learning** with modern object detection techniques, the system efficiently classifies genders in images.

## Features
- **Face Detection**: Utilizes **YOLOv8** for accurate and fast face detection.
- **Gender Classification**: A **pre-trained VGG16 model** classifies detected faces.
- **Preprocessing**: Detected faces are cropped, padded, and resized to **224x224** for consistent model input.
- **Bounding Box Visualization**: Displays detected faces with corresponding gender labels.


pip install tensorflow tensorflow-hub opencv-python matplotlib ultralytics
