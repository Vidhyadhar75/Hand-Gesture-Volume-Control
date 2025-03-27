# Hand Gesture Volume Control

## 📌 Project Overview
This project implements a **hand gesture-based volume control system** using OpenCV and MediaPipe. By detecting the distance between the thumb and index finger, it adjusts the system's volume dynamically.

## 🚀 Features
- **Real-time hand tracking** using MediaPipe.
- **Gesture-based volume control** using Pycaw.
- **Volume level visualization** with a progress bar.
- **Smooth and responsive adjustments.**
- **Press 'SPACE' to exit the application.**

## 📂 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Vidhyadhar75/Hand-Gesture-Volume-Control.git
   cd Hand-Gesture-Volume-Control
   ```
2. Install dependencies:
   ```bash
   pip install opencv-python mediapipe numpy pycaw
   ```

## 🛠 Usage

Run the script:
```bash
python volumecontrol.py
```

## 📊 How It Works
- Captures video from the webcam.
- Detects hand landmarks using **MediaPipe Hands**.
- Measures the distance between the **thumb and index finger**.
- Maps this distance to **system volume levels**.
- Displays a **volume bar** for real-time feedback.
- Press `SPACE` to exit the program.

## 🤖 Technologies Used
- OpenCV
- MediaPipe
- Pycaw
- Python

## 📌 Contribution
Pull requests are welcome! Improve tracking accuracy or add more gesture controls.

![image](https://github.com/user-attachments/assets/d0c5dc50-be45-457d-beaa-0f5ec8cd1699)

