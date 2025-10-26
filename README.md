🚗 Object Tracking and Counting using YOLO and OpenCV
📘 Description

This project implements a real-time object tracking and counting system using YOLO and OpenCV. It detects and tracks multiple objects in a video feed and counts them as they cross a predefined horizontal line. Each detected object is assigned a unique tracking ID, ensuring accurate counting without duplication. The results, including bounding boxes, class labels, IDs, and live counts, are displayed on the video frames.
This implementation is optimized for Google Colab, using cv2_imshow for frame visualization.

Features

• Real-time object detection and tracking
• Automatic counting of objects crossing a reference line
• Class-wise count visualization on video frames
• Unique ID assignment for each tracked object
• Fully compatible with Google Colab environment


Workflow

• Load a video feed or camera stream for processing.
• The YOLO model detects and tracks objects across frames
• A red line is drawn as a counting threshold.
• When an object crosses this line, its class count increases automatically.
• The frame displays live tracking, object information, and cumulative counts.

