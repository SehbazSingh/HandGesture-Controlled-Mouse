# Hand Gesture Mouse Control

A Python-based virtual mouse system that uses hand gestures detected via a webcam to control mouse movements and actions like left click, right click, double click, and taking screenshots. The system utilizes MediaPipe for hand tracking, OpenCV for video processing, and PyAutoGUI for controlling the system mouse.

## Features

- **Cursor Movement** – Move the mouse cursor using your index finger with a contracted thumb.
- **Left Click** – Triggered by bending the index fingure and expanding the thumb. 
- **Right Click** – Triggered by bending the middle fingure and expanding the thumb.
- **Double Click** – Triggred by bending both index and middel fingure and expanding the thumb.
- **Screenshot Capture** – Take screenshots by contracting the hand in a fist gesture.

## Requirements

Install the dependencies using pip:

```bash
pip install opencv-python mediapipe pynput pyautogui numpy
