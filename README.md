# Gesture Controlled V-Mouse

A computer vision-based virtual mouse built using Python, OpenCV, and MediaPipe.

## Features

* Real-time hand tracking
* Cursor movement using gestures
* Left click, right click, drag and drop
* Scroll support
* Gesture smoothing for stable cursor control

## Tech Stack

* Python
* OpenCV
* MediaPipe
* PyAutoGUI

## How It Works

The system captures webcam frames using OpenCV and detects hand landmarks using MediaPipe. Different finger configurations are mapped to mouse actions such as movement, clicks, dragging, and scrolling.

## Run Locally

conda activate mouse_fix
python Gesture_Controller.py

