Virtual Mouse using Hand Gestures

Overview

This project implements a virtual mouse using hand gestures, leveraging computer vision and deep learning techniques. It uses OpenCV for video processing, MediaPipe for hand tracking, and PyAutoGUI for simulating mouse actions. Additionally, the project can control system brightness and volume through specific hand gestures.

Features

Cursor Control: Move the mouse pointer using hand movements.

Clicking Actions:

Left Click (Fist Gesture)

Right Click (Index Finger Gesture)

Double Click (Two-Finger Closed Gesture)

Scrolling: Scroll up/down using pinch gestures.

Volume Control: Adjust system volume with a major pinch gesture.

Brightness Control: Adjust screen brightness with a minor pinch gesture.

Technologies Used

Python

OpenCV

MediaPipe

PyAutoGUI

Screen Brightness Control

Pycaw (for audio control)

Installation

Prerequisites

Ensure you have Python 3.x installed along with the following dependencies:

pip install opencv-python mediapipe pyautogui screen-brightness-control pycaw comtypes google protobuf

Usage

Run the Python script:

python virtual_mouse.py

The webcam will start, detecting hand gestures.

Use the predefined gestures to control the mouse and system settings.

Press Enter to exit the program.

Hand Gesture Mapping

Gesture

Action

V Gesture

Move cursor

Fist

Left Click

Index Finger

Right Click

Two Fingers Closed

Double Click

Pinch Minor

Scroll

Pinch Major

Adjust Brightness / Volume

How It Works

Hand Tracking: Uses MediaPipe Hands to track hand landmarks in real time.

Gesture Recognition: Converts landmark positions into recognizable gestures.

Action Execution: Maps detected gestures to corresponding mouse or system control actions.

Noise Reduction: Uses a stabilization algorithm to prevent unintended movements.

Future Enhancements

Adding gesture-based text input.

Enhancing gesture accuracy with ML models.

Multi-hand gesture support for advanced control.
