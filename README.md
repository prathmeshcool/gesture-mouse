# Virtual Mouse with Gestures

A real-time gesture-controlled virtual mouse built using Python, OpenCV, and MediaPipe.

## Features

* Real-time hand tracking
* Cursor movement using gestures
* Left click and right click
* Drag and drop support
* Scroll control
* Cursor smoothing for stable movement

## Tech Stack

* Python
* OpenCV
* MediaPipe
* PyAutoGUI

## How It Works

The system captures webcam frames using OpenCV and detects hand landmarks using MediaPipe. Finger positions and landmark distances are analyzed to classify gestures, which are then mapped to mouse actions such as cursor movement, clicking, dragging, and scrolling.

## Run Locally

```bash
conda activate mouse_fix
python Gesture_Controller.py
```
