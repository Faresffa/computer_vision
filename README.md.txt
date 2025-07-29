This mini-project demonstrates how to use the open-source [Supervision](https://github.com/roboflow/supervision) library to automatically detect players in a tennis video using YOLOv8.

## 🎯 Goal
Apply real-time object detection to a 30-second tennis rally (Alcaraz vs Sinner, Roland-Garros 2025).

## 📦 Tech Stack
- Python
- [Supervision](https://github.com/roboflow/supervision)
- Ultralytics YOLOv8
- OpenCV

## 🛠️ What I did
- Used the official `supervision` YOLOv8 example notebook
- Replaced their demo video with my own 30-second tennis video
- Got real-time player detection, exported annotations

## ✅ Output
- Annotated video (bounding boxes on players)
- Detection results in CSV

## 📂 File Structure
- `tennis_point.mp4`: Your input video
- `notebooks/`: Jupyter notebook to run the detection
- `output/`: Annotated video and CSV
