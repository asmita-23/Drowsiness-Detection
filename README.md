# Drowsiness Detection System

![Drowsiness Detection](https://kajabi-storefronts-production.kajabi-cdn.com/kajabi-storefronts-production/file-uploads/blogs/22606/images/df43de2-1275-7872-ce38-fd1be6e33_ezgif.com-resize_5_.gif)

## Overview
This project is a real-time **Drowsiness Detection System** that monitors driver alertness using **computer vision** and **facial landmark detection**. It detects drowsiness by analyzing the **Eye Aspect Ratio (EAR)** and triggers an alert if the driver appears to be drowsy.

## Features
- **Real-time face and eye detection** using OpenCV and Dlib
- **EAR calculation** to determine eye closure duration
- **Audio/Visual alert system** when drowsiness is detected
- **Works with any webcam** for easy implementation

## Technologies Used
- Python
- OpenCV
- Dlib
- NumPy
- SciPy
- Playsound (for alert sound)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/drowsiness-detection.git
   cd drowsiness-detection
   ```
2. Install dependencies:
   ```bash
   pip install opencv-python dlib numpy scipy playsound
   ```

## Usage
Run the script to start detection:
```bash
python drowsiness_detector.py
```
- Make sure your webcam is connected.
- If drowsiness is detected, an alert sound will play.

## How It Works
1. Captures video from the webcam
2. Detects the driver's face and eyes
3. Computes the **Eye Aspect Ratio (EAR)**
4. If EAR remains low for a certain duration, it triggers an alert


## Future Improvements
- Improve accuracy with deep learning models (e.g., CNNs)
- Add head pose detection for better drowsiness prediction
- Mobile app integration




