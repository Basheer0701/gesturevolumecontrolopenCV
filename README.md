# Gesture Volume Control

A real-time hand gesture recognition project that adjusts the system volume based on finger gestures using computer vision techniques.

---

## Features
- Detects hand gestures in real-time.
- Adjusts system volume based on the distance between the thumb and index finger.

---

## Technologies Used
- **Python**: Core programming language.
- **OpenCV**: For image processing and computer vision.
- **MediaPipe**: For hand tracking and detecting landmarks.
- **PyCaw**: For controlling system audio volume.

---

## How It Works
1. The system captures video from the webcam and processes it using OpenCV.
2. Hand landmarks are detected using MediaPipe's hand tracking module.
3. The distance between the thumb and index finger is calculated.
4. This distance is mapped to system volume levels, ranging from 0% to 100%.
5. Visual indicators, such as lines and points, are drawn on the detected hand to provide real-time feedback.

---
