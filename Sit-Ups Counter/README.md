AI Sit-Up Counter Using Computer Vision

A real-time AI-based sit-up counter that uses MediaPipe Pose Estimation and OpenCV to detect body movements and automatically count repetitions using joint angle calculations.

Features
Real-time pose detection using webcam
Automatic sit-up repetition counting
Knee angle calculation for movement analysis
Live display of pose landmarks, angle, stage, and rep count
Works with different webcam indexes
Tech Stack
Python
OpenCV – Video processing
MediaPipe Pose Landmarker – Human pose detection
NumPy – Mathematical calculations
How It Works
Captures live video through webcam using OpenCV.
Detects body landmarks using MediaPipe Pose Estimation.
Extracts hip, knee, and ankle coordinates.
Calculates the knee joint angle.
Tracks movement stages:
Bent position → angle < 110°
Straight position → angle > 150°
Counts one repetition after a complete movement cycle.