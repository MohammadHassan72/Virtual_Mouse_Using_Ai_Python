# Virtual Mouse Using AI Python

## Overview
This project implements a virtual mouse control system using hand gestures recognized by AI. It leverages computer vision techniques and the MediaPipe library for hand tracking and gesture recognition, enabling users to interact with their computer without physical input devices such as a mouse or keyboard.

## Features
- Hand tracking and landmark detection using MediaPipe
- Recognition of predefined hand gestures for mouse control
- Implementation of various mouse actions including cursor movement, clicking, scrolling, and system settings adjustment
- Support for multiple hand gestures and simultaneous tracking of both hands

## Requirements
- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI
- Math
- Enum

## Installation
1. Clone or download the project repository.
2. Install the required Python packages using pip:
   ```
   pip install opencv-python mediapipe pyautogui
   ```
3. Run the main Python script to start the virtual mouse control:
   ```
   python virtual_mouse.py
   ```

## Usage
1. Ensure your webcam is properly connected and positioned.
2. Run the Python script to start the virtual mouse control system.
3. Perform hand gestures within the camera frame to control the virtual mouse:
   - Move your hand to move the mouse cursor.
   - Make specific gestures for actions like clicking, scrolling, and adjusting system settings.
4. Press the Enter key to exit the virtual mouse control.

## Contributors
  @MySelf

## License
This project is licensed.

---
