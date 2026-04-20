# Colour-Detection
A basic algorithm that detects colors in images using OpenCV. It converts images to HSV format, applies predefined color ranges, and identifies matching pixels. Useful for real-time detection, object tracking, and beginner computer vision projects.
This project implements a simple and efficient color detection algorithm that identifies the dominant color in an image or detects colors in real-time using a webcam. It is built using fundamental image processing techniques and is suitable for beginners exploring computer vision.

#🚀 Overview

The algorithm processes an input image by analyzing pixel values and comparing them with predefined color ranges. Based on this comparison, it classifies and labels the detected colors.

#⚙️ How It Works
The input image is read using an image processing library like OpenCV.
The image is converted from BGR to HSV color space for better color segmentation.
Predefined HSV ranges are used to create masks for specific colors.
The algorithm checks pixel values within these ranges to detect colors.
Detected regions are highlighted, and corresponding color names are displayed.

#🧠 Key Concepts Used
Image processing
Color space conversion (BGR → HSV)
Masking and thresholding
Contour detection

#💡 Features
Detects basic colors like Red, Green, Blue, Yellow, etc.
Works on both static images and live webcam feed
Lightweight and easy to understand
Beginner-friendly implementation

#📌 Applications
Object tracking
Image filtering
Robotics and automation
Assistive tools for color recognition

#🛠️ Tech Stack
Python
OpenCV
NumPy
