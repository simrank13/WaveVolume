# WaveVolume

## Hand Gesture Volume Control using Python, OpenCV, and MediaPipe

WaveVolume is a computer vision project that lets users control their system’s audio volume using simple hand gestures captured through a webcam. The program detects the thumb and index finger distance in real time and adjusts the system volume accordingly — hands-free control through motion!

## Technologies Used
- **Python 3.10+**
- **OpenCV** – image processing and webcam input
- **MediaPipe** – real-time hand landmark detection (powered by TensorFlow Lite)
- **TensorFlow Lite** – backend model inference engine
- **PyAutoGUI** – system volume control automation

## Features

- Real-time hand tracking using MediaPipe

- Distance calculation between thumb and index finger

- Dynamic volume control via PyAutoGUI

- Cleanly exits when you click the esc button

## How It Works

- Capture webcam input using OpenCV.

- Detect hand landmarks with MediaPipe’s Hands model.

- Measure the distance between the index finger and thumb tips.

- If the fingers are far apart, volume increases and if close together, volume decreases.


## Installation
- Clone the repository:
  git clone https://github.com/simrank13/WaveVolume.git
  cd WaveVolume
  pip install opencv-python mediapipe pyautogui
- python volume_control_python.py






