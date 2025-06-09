# 🏋️‍♂️ Human Pose Detection for Exercise Monitoring Using Machine Learning (MediaPipe)

This repository contains the implementation of my Master's Thesis Project: **Human Pose Detection for Exercise Monitoring Using Machine Learning (MediaPipe)**.


## 🧠 Project Overview

This project explores how MediaPipe-based human pose detection can be used to support home fitness and physical well-being, where access to personal trainers and professional gym guidance may be limited.

The system captures real-time human pose through webcam input, analyzes body landmarks (keypoints), calculates joint angles (like the elbow), counts exercise repetitions, and provides on-screen feedback about posture correctness.


## 🔧 Technologies Used

- **Python** (Jupyter Notebook)
- **MediaPipe** – for real-time human pose estimation
- **OpenCV** – for webcam video capture and frame rendering
- **NumPy** – for numerical computations


## 🚀 Features

- 🎯 Real-time human pose detection using MediaPipe
- 🦾 Tracks **Bicep Curls** (both left and right arms)
- 🏋️ Tracks **Squats** with both legs
- 📐 Visualizes joint angles and posture feedback
- 🔄 Exercise switching: Bicep Curl ↔️ Squat
- 👈 Switch sides for curls (left/right)
- 🔁 Repetition counter with range-of-motion (ROM) detection
- ⌨️ Keyboard Controls


## 🖥️ How to Run

### 1. Clone the Repository
git clone https://github.com/nnirajan/pose-detection.git
cd pose-detection

### 2. Install Requirements
pip install -r requirements.txt

### 3. Launch the Jupyter Notebook
jupyter notebook

Then open implementation.ipynb and run


## Notes:
The current version supports Bicep Curls and Squats; additional exercises may be integrated in future updates based on research scope and user feedback.
