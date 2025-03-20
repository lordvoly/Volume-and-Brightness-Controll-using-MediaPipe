# Hand Gesture Volume and Brightness Control

## Overview
This Python application uses computer vision and hand tracking to control system volume and screen brightness through hand gestures. Leveraging MediaPipe for hand detection and OpenCV for video processing, users can adjust volume and brightness by moving their fingers in a designated region of the webcam frame.

## Features
- Real-time hand tracking using MediaPipe
- Volume control with right hand gesture
- Screen brightness control with left hand gesture
- Visual feedback through on-screen displays
- Easy-to-use interface with webcam input

## Prerequisites
- Python 3.7+
- Webcam

## Installation

### Required Dependencies
```bash
pip install opencv-python
pip install mediapipe
pip install screen-brightness-control
pip install pycaw
pip install comtypes
```

## How It Works
- The application uses a specific region of interest (ROI) in the webcam frame
- Right hand controls volume: Pinch distance between thumb and index finger maps to volume level
- Left hand controls screen brightness: Pinch distance between thumb and index finger maps to brightness level
- Displays real-time hand tracking and current volume/brightness levels

## Usage Instructions
1. Run the script
2. Position your hand in the designated rectangular region
3. For volume control: Use right hand, pinch thumb and index finger
   - Closer pinch = Lower volume
   - Wider pinch = Higher volume
4. For brightness control: Use left hand, pinch thumb and index finger
   - Closer pinch = Lower brightness
   - Wider pinch = Higher brightness
5. Press 'q' to quit the application

## Limitations
- Requires good lighting conditions
- Works best with clear hand gestures
- Depends on webcam quality

## Dependencies
- OpenCV
- MediaPipe
- Screen Brightness Control
- PyCAW (Python Core Audio Windows)
- ComTypes

## Troubleshooting
- Ensure webcam is not in use by another application
- Check lighting conditions
- Verify all dependencies are correctly installed



## Author
Aryan Batheja
University Of Aberdeen
