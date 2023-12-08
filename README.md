# eye_conrolled_mouse
# Eye Controlled Mouse using MediaPipe and PyAutoGUI

This Python script demonstrates a basic implementation of an eye-controlled mouse using the MediaPipe library for face landmark detection and PyAutoGUI for mouse control.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- MediaPipe (`pip install mediapipe`)
- PyAutoGUI (`pip install pyautogui`)

## Usage

1. Install the required packages by running:
   ```bash
   pip install opencv-python mediapipe pyautogui

Run the script:
python eye_controlled_mouse.py
Adjust the camera to capture your face.

Move your eyes to control the mouse pointer.

Blink both eyes to simulate a click action.
Code Explanation
The script captures video from the default camera using OpenCV.
It uses the MediaPipe library to detect facial landmarks, particularly focusing on eye and face features.
PyAutoGUI is employed to control the mouse cursor based on the movement of specific facial landmarks.
Blinking both eyes triggers a mouse click.
Important Notes
Ensure that your camera is properly positioned to capture your face.
Adjust the face and eye landmark indices based on your camera and face orientation.
Credits
This script is based on the functionality provided by the MediaPipe and PyAutoGUI libraries.
License
This project is licensed under the MIT License.

Remember to customize the readme according to your specific project details and provide any additional information that might be helpful for users.
