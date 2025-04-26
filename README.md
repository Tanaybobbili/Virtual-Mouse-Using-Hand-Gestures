Virtual Mouse Using Hand Gestures

Overview

This project implements a Virtual Mouse that enables users to control their system using hand gestures, leveraging computer vision and deep learning techniques. It utilizes OpenCV for video processing, MediaPipe for hand tracking, and PyAutoGUI for simulating mouse actions. Additionally, users can control system brightness and volume through specific hand gestures.

Features

🎯 Cursor Control – Move the mouse pointer using hand movements.
🖱️ Clicking Actions:
Left Click – Fist Gesture
Right Click – Index Finger Gesture
Double Click – Two-Finger Closed Gesture
🔄 Scrolling – Scroll up/down using pinch gestures.
🔊 Volume Control – Adjust system volume with a major pinch gesture.
💡 Brightness Control – Adjust screen brightness with a minor pinch gesture.

Technologies Used

Python
OpenCV – Real-time video processing
MediaPipe – Hand tracking and gesture recognition
PyAutoGUI – Simulating mouse actions
Screen Brightness Control – Adjusting screen brightness
Pycaw – Audio volume control

Prerequisites

Ensure you have Python 3.x installed, then install the required dependencies:
pip install opencv-python mediapipe pyautogui screen-brightness-control pycaw comtypes google protobuf

Usage

Run the Python script:
python virtual_mouse.py

The webcam will start detecting hand gestures.
Use the predefined gestures to control the mouse and system settings.
Press Enter to exit the program.
Hand Gesture Mapping
Gesture -	Action
V Gesture	- Move Cursor
Fist - Left Click
Index Finger - Right Click
Two Fingers Closed	- Double Click
Pinch Minor -	Scroll
Pinch Major -	Adjust Brightness / Volume

How It Works

✅ Hand Tracking – Uses MediaPipe Hands to track hand landmarks in real time.
✅ Gesture Recognition – Converts landmark positions into recognizable gestures.
✅ Action Execution – Maps detected gestures to corresponding mouse or system control actions.
✅ Noise Reduction – Uses a stabilization algorithm to prevent unintended movements.

Future Enhancements

🚀 Gesture-Based Text Input – Enable users to type using gestures.
🚀 Improved Accuracy – Enhance gesture detection using ML models.
🚀 Multi-Hand Support – Advanced gesture controls using both hands.

Contributors

👨‍💻 Bobbili Hanuma Tanay
👨‍💻 Indana Narsarao
👨‍💻 Vanaparthi Purna chand

⭐ If you like this project, give it a star! 🌟
