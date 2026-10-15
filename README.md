# Spine & Posture Screening Prototype 📐

An experimental computer-vision application built with Streamlit and MediaPipe to estimate visible postural asymmetry and body alignment from photographs.

## Features

- **Scoliosis Screening (Front/Back View):** 
  - Estimates shoulder tilt and hip tilt angles.
  - Measures vertical height differences in pixels between left and right landmarks.
  - Generates postural asymmetry bar charts and downloadable CSV reports.
- **Kyphosis Screening (Side View):** 
  - Analyzes ear-to-shoulder (head posture) and shoulder-to-hip (trunk posture) vertical inclination angles.
  - Automatically selects the side profile with higher landmark visibility.
  - Provides screening threshold alerts and medical consultation guidance.
  - Exports measurement summaries and quality checks to CSV.

## Repository Structure

```text
├── app.py                      # Main Streamlit application
├── requirements.txt            # Python package dependencies
├── pose_landmarker_lite.task   # MediaPipe Pose Landmarker model
└── README.md                   # Project documentation
