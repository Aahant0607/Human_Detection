# 🎯 Human Detection

A real-time human detection system that analyzes YouTube video streams and identifies people using YOLOv8 object detection model.

## 📋 Overview

This project enables real-time human detection on YouTube videos using state-of-the-art YOLOv8 deep learning model. It streams videos directly from YouTube without downloading them, processes frames in real-time, and displays bounding boxes with confidence scores for each detected person.

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| **Object Detection** | YOLOv8 (Ultralytics) |
| **Video Processing** | OpenCV (cv2) |
| **YouTube Streaming** | yt-dlp |
| **Deep Learning Framework** | PyTorch (via Ultralytics) |
| **Programming Language** | Python 3.x |
| **License** | MIT License |

## ✨ Features

- ✅ Real-time human detection on YouTube videos
- ✅ Direct streaming (no download required)
- ✅ YOLOv8 nano model for fast inference
- ✅ Bounding box visualization with confidence scores
- ✅ Person count display on video
- ✅ Efficient frame resizing for performance optimization
- ✅ Keyboard exit control (press 'q' to quit)

## 📦 Installation

### Prerequisites
- Python 3.7+
- pip package manager

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Aahant0607/Human_Detection.git
   cd Human_Detection
