# Vehicle Counter System using Python, OpenCV, and YOLOv5

## Overview

The Vehicle Counter System is a real-time vehicle counting solution that uses computer vision techniques to detect and count vehicles from video footage. This system leverages YOLOv5 (You Only Look Once version 5) for object detection and OpenCV for video processing.

## Features

- **Real-Time Vehicle Detection:** Detects vehicles in real-time from video footage.
- **Vehicle Counting:** Counts the number of vehicles passing through a specified checkpoint.
- **Data Logging:** Optionally logs vehicle counts to a file for later analysis.
- **Visualization:** Displays the video with bounding boxes around detected vehicles and the current count.

## Components

- **Python:** Programming language used for implementation.
- **OpenCV:** Library for video processing and computer vision.
- **YOLOv5:** Object detection model for detecting vehicles.
- **Video Source:** Can be a webcam or a video file.

## Installation

### Prerequisites

- **Python 3.x:** Make sure Python 3.x is installed on your system.
- **Pip:** Python package installer.

### Dependencies

Install the required Python packages using pip:

```bash
pip install opencv-python-headless
pip install torch torchvision torchaudio
pip install yolov5
pip install matplotlib
