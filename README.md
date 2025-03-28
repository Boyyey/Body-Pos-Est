# Real-Time Pose Estimation and Form Correction 📷💪

## Overview
This Python project utilizes OpenCV and MediaPipe to track body posture in real time via a webcam. It detects key body landmarks, calculates the angle of the right arm (shoulder-elbow-wrist), and provides live feedback to help maintain proper exercise form. 

## Features ✨
- 📌 **Real-time Pose Tracking**: Uses MediaPipe to detect body landmarks.
- 🔢 **Angle Calculation**: Computes the angle between shoulder, elbow, and wrist.
- ✅ **Instant Feedback**: Provides guidance on arm positioning for better form.
- 🎨 **Live Visualization**: Draws landmarks and displays angles on the screen.
- 🏋️ **Exercise Monitoring**: Helps in form correction for workouts.

## Installation ⚙️
Make sure you have Python installed, then install the required dependencies:
```bash
pip install opencv-python mediapipe numpy
```

## Usage ▶️
Run the script using:
```bash
python script.py
```

- Ensure your webcam is connected.
- Follow the on-screen angle display and feedback.
- Press **'q'** to exit.

## How It Works 🛠️
1. Captures live video feed from the webcam.
2. Uses MediaPipe Pose to detect body landmarks.
3. Extracts coordinates of the shoulder, elbow, and wrist.
4. Calculates the arm's angle and displays it on the screen.
5. Provides real-time feedback on form correction.

## Example Feedback Messages 📢
- **"Lower arm more!"** (If angle > 160°)
- **"Raise arm up!"** (If angle < 30°)
- **"Good form!"** (If angle is optimal)

## Future Enhancements 🚀
- Add support for left arm tracking.
- Implement tracking for other exercises.
- Enhance UI with graphical overlays.

## Contributing 🤝
Feel free to fork the repo and submit pull requests! Suggestions and improvements are always welcome.

