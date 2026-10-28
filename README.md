# Cheating Tracking and Alert System

## 📌 Project Overview
The **Cheating Tracking and Alert System** is a computer vision project designed to assist in monitoring student behavior during exams using video analysis.

The system detects and tracks people in classroom footage and explores suspicious head movements as potential indicators for further review. It aims to support exam monitoring by highlighting behaviors that may require human attention.

**Note:** Head movement alone does not prove cheating. Alerts should be reviewed by a human.

## 🎯 Objectives
- Detect people in classroom videos.
- Track detected people and assign IDs.
- Visualize tracking results using bounding boxes.
- Explore suspicious behavior detection.
- Support incident documentation and future alerting features.

## 🛠️ Technologies Used
- Python
- OpenCV
- Ultralytics YOLO
- ByteTrack
- MediaPipe
- Pandas
- Jupyter Notebook

## ⚙️ Current Features
- Person detection in video frames.
- Multi-person tracking with IDs.
- Annotated video output.
- Experimental face-landmark analysis.
- Initial exploration of suspicious-behavior review.

## 🚧 Future Improvements
- Improve gaze and head-direction estimation.
- Reduce false-positive alerts.
- Add a graphical user interface using Tkinter.
- Save incident screenshots and structured alert logs.
- Test performance on more classroom videos.

## ▶️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Marinastudent-hub/CheatingTrackingSystem.git
cd CheatingTrackingSystem
```

### 2. Create a virtual environment
```bash
python -m venv .venv
```

Activate it on Windows:
```bash
.venv\Scripts\activate
```

### 3. Install dependencies
Install the required packages used by the notebook:
```bash
pip install ultralytics opencv-python mediapipe pandas jupyter
```

### 4. Run the notebook
Open the project folder in VS Code, open the Jupyter Notebook, and run the cells in order.

Place the test video in the expected input folder before running the video-analysis cells.

## ⚠️ Limitations
This is an experimental computer vision project. Looking away, turning one's head, or looking down may be normal exam behavior. The system's outputs are indicators for human review, not definitive evidence of cheating.


