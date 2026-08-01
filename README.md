# AI-Powered Exercise Pose Estimation and Repetition Counter

A computer vision project that performs real-time human pose estimation, exercise recognition, posture analysis, and repetition counting using MediaPipe and OpenCV.

The system detects body landmarks from a webcam, calculates joint angles, evaluates posture quality, counts repetitions for multiple exercises, records workout sessions, and stores exercise statistics for later analysis.

---

## Overview

This project was developed to explore the application of computer vision in fitness monitoring. Instead of relying on wearable sensors, the system estimates body posture directly from video frames and provides real-time feedback.

The implementation combines MediaPipe Pose with OpenCV to identify body landmarks, calculate joint angles, and analyze movement patterns for different exercises.

---

## Features

- Real-time pose estimation
- Automatic exercise detection
- Joint angle calculation
- Posture evaluation
- Exercise repetition counting
- Workout statistics
- Video recording
- CSV data logging
- Live visualization
- Performance graphs

---

## Supported Exercises

The system currently supports multiple exercises including:

- Bicep Curls
- Squats
- Shoulder Press
- Push-ups
- Lunges
- Deadlifts
- Tricep Extensions
- Lateral Raises
- Plank
- Crunches
- Leg Raises
- Pull-ups
- Dumbbell Rows
- Additional bodyweight exercises

---

## Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/AI-Powered-Exercise-Pose-Estimation.git
```

Move into the project

```bash
cd AI-Powered-Exercise-Pose-Estimation
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Run

```bash
python main.py
```

The webcam will open automatically.

Press **Q** to exit.

---

## Output

During execution the project can

- Detect body landmarks
- Count repetitions
- Display joint angles
- Record workout videos
- Save exercise statistics
- Export CSV files
- Generate performance plots

---

## Folder Description

| Folder | Purpose |
|---------|----------|
| src | Core implementation |
| notebooks | Development notebook |
| recordings | Recorded workout videos |
| outputs | CSV files and graphs |
| images | Screenshots |
| docs | Documentation |

---

## Future Improvements

- Support more exercises
- Deep learning based exercise classification
- Mobile deployment
- Personalized feedback
- Workout history dashboard
- Multi-person tracking

---

---

## Author

**Khan Hameedullah**

M.Sc. Information and Communication Engineering  
University of Electronic Science and Technology of China (UESTC)

GitHub: https://github.com/KhanHameedullah

---

If you found this project useful, consider giving it a ⭐ on GitHub.
