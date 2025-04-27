# Pose Estimation Project

This project demonstrates the use of MediaPipe's **Holistic** model for real-time pose, face, and hand landmarks detection using a webcam. The application utilizes **OpenCV** for capturing frames and displaying the detected landmarks.

## Prerequisites

Make sure you have the following installed:

- Python 3.x
- `opencv-python`
- `mediapipe`
- `numpy`

## Installation

To set up the environment, run the following commands:

```bash
pip install opencv-python mediapipe numpy

----

## 📸 Screenshot
![Screenshot 2025-04-27 at 12 59 36 PM](https://github.com/user-attachments/assets/f8c637c7-2369-4f76-b38e-7fb210ac4d91)

## Code Overview
1. Imports:
We import the required libraries, cv2 for OpenCV and mediapipe for pose and face detection.

2. MediaPipe Holistic Setup:
We initialize the Holistic model from MediaPipe, which allows us to detect pose, face, and hand landmarks in real-time.

3. OpenCV Camera Setup:
We open the webcam and configure its settings such as exposure and brightness.

4. Processing Frames:
Pose Landmarks: Detected pose landmarks are drawn on the frame.

Face Landmarks: Detected face landmarks are drawn as contours.

Hand Landmarks: Detected hand landmarks are drawn.

5. Display Output:
The frame with detected landmarks is displayed in a window. Press 'q' to exit the loop.

## 🎥 Explanation Video

🎥 [Watch the Video](https://www.linkedin.com/posts/sathiyapriya-s-22ucs048_facedetection-ai-computervision-activity-7237469650450554880-Q7rZ?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEKubiABTjioeFLfoGOrHXFNNCGvYJ6moX8)
