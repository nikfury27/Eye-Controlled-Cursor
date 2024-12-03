# Eye Controlled Cursor

An innovative project that enables users to control the computer cursor using eye movements, enhancing accessibility and interaction for individuals with physical disabilities or those seeking hands-free computing solutions.

---

## Features
- **Eye Tracking**: Detects and tracks the user's eye movements in real time.
- **Cursor Control**: Moves the computer cursor based on gaze direction.
- **Click Simulation**: Supports blinking or gaze dwell for left/right mouse clicks.
- **Custom Calibration**: Allows users to calibrate the system for improved accuracy.
- **Multi-Platform Support**: Compatible with major operating systems.

---

## How It Works
1. **Eye Detection**: Uses a webcam to capture real-time video of the user's face and eyes.
2. **Gaze Estimation**: Detects the position and movement of the eyes using computer vision.
3. **Cursor Mapping**: Maps the gaze coordinates to the screen space to control the cursor.

---

## Installation

### Prerequisites
- Python 3.7 or newer
- A functional webcam

### Libraries and Tools
Install the required libraries by running:

```bash
pip install opencv-python mediapipe pyautogui numpy
```

### Clone the Repository
```bash
git clone https://github.com/yourusername/eye-controlled-cursor.git
```

---



## Future Enhancements
- **Enhanced Accuracy**: Improve gaze estimation using advanced models.
- **Support for Multiple Monitors**: Expand functionality to multi-screen setups.
- **Custom Gestures**: Enable user-defined gestures for clicks and drag-and-drop.
- **AI Integration**: Use deep learning models for more robust eye tracking.

---
