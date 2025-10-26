Object Tracking and Counting with YOLO and OpenCV

This project performs object detection, tracking, and counting using YOLO and OpenCV in Google Colab. It detects and tracks multiple objects in a video stream and counts how many cross a defined reference line.

Overview

The system:

Detects and tracks objects using a YOLO model.

Draws bounding boxes and assigns unique IDs to each object.

Defines a red reference line in the frame.

Counts how many tracked objects cross that line.

Displays live counts of each object class on the video frames.

Features

Real-time object detection and tracking

Accurate cross-line counting logic

Class-wise object counting

ID-based tracking to avoid duplicate counts

Visualization with bounding boxes, IDs, and dynamic counts

Works directly in Google Colab using cv2_imshow
