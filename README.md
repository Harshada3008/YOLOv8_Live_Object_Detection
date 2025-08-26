# YOLOv8_Live_Object_Detection

<img width="1909" height="922" alt="Screenshot 2025-08-26 182751" src="https://github.com/user-attachments/assets/990b86d9-037e-4311-b834-433ad9dabaea" />

Real-time object detection using YOLOv8 + OpenCV 🎥. Streams webcam feed, detects objects with bounding boxes &amp; labels, and overlays FPS. Supports saving snapshots. Built for fast inference, lightweight deployment, and easy customization. Ideal for computer vision, AI demos, and surveillance projects.
🖼️ YOLOv8 Live Object Detection
📌 Overview

This project implements a real-time object detection system using the YOLOv8 model from Ultralytics and OpenCV for live webcam streaming. The application detects objects in the camera feed, draws bounding boxes with labels, displays FPS, and allows snapshot saving.

🔹 Features

🎥 Live Webcam Detection – Capture frames in real-time.

🧠 YOLOv8 Inference – Leverages pretrained YOLOv8 (nano/small) for high-speed detection.

⚡ FPS Counter – Real-time performance tracking.

💾 Snapshot Support – Save annotated frames with one keystroke.

🖼️ Customizable – Change YOLO model (e.g., yolov8s.pt) for accuracy/speed tradeoff.

🔹 Installation
# Clone the repository
git clone https://github.com/your-username/YOLOv8_Live_Object_Detection.git
cd YOLOv8_Live_Object_Detection

# Install dependencies
pip install -r requirements.txt


Requirements

Python 3.8+

OpenCV

Ultralytics (YOLOv8)

NumPy

🔹 Usage
python live_detection.py


Controls:

Press q → Quit

Press s → Save snapshot

🔹 Output

Live window with detected objects and FPS overlay

Snapshots saved in runs/snapshots/

🔹 Tech Stack

YOLOv8 (Ultralytics) – Deep learning object detection

OpenCV – Video capture & visualization

Python – Core programming

🎯 Applications

Security & surveillance

AI/ML demos

Smart monitoring systems

Computer vision experiments
