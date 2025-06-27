# Person Detection and Tracking Using YOLO and Deep SORT

This project demonstrates real-time **person detection** and **multi-object tracking** using the **YOLOv5 object detection model** integrated with the **Deep SORT tracking algorithm**. It processes live webcam feed or video files, detects persons using YOLO, and assigns unique IDs to each tracked person.

---

## 🔍 Overview

- **YOLOv10** is used for fast and accurate person detection.
- **Deep SORT** (Simple Online and Realtime Tracking) assigns unique IDs to each person and maintains identity across frames.
- You can use this on:
  - Video files (e.g., `.mp4`)
  - Live webcam feed

---

## 🚀 Features

- Real-time person detection
- Multi-object tracking with consistent IDs
- Works on pre-recorded videos or webcam
- Bounding boxes with ID overlays
- Option to save the output video with tracking results

## 📉 Limitations

- Low FPS / Performance Bottleneck
- Real-time performance can suffer, especially on CPUs or low-end GPUs.

- YOLOv10 + Deep SORT is computationally expensive and may run at: Low FPS (1-2 FPS) on laptops or systems without powerful GPUs.
- Even lower FPS for live webcam detection due to real-time frame capturing, pre-processing, and inference.

