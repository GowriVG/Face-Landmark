Real-Time Face Landmark Detection using MediaPipe and OpenCV
This Python script uses MediaPipe and OpenCV to detect and display facial landmarks in real-time from a webcam feed. It utilizes MediaPipe's FaceMesh solution to identify 468 facial landmarks and overlay them on the live video stream captured from your camera.

Features:
Captures real-time video using OpenCV

Converts frames to RGB for processing

Detects facial landmarks using MediaPipe’s FaceMesh

Draws small blue circles on each detected facial landmark

Press q to exit the video window

Requirements:
Python 3.x
OpenCV (opencv-python)
MediaPipe

How to Run:
Install dependencies: pip install opencv-python mediapipe

Run the script: python face_landmarks.py

Note: Make sure your webcam is connected. This script opens a window showing your face with tracked landmarks in real time.
