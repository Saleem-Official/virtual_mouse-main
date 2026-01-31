# virtual Mouse

virtual Mouse is a Python project that uses your webcam and hand tracking to control your mouse cursor with gestures. It leverages OpenCV for video capture, Mediapipe for hand landmark detection, and PyAutoGUI for controlling the mouse on your screen.

## Features
- Move your mouse cursor by moving your index finger in front of your webcam.
- Click by bringing your thumb and index finger close together.

## Requirements
- Python 3.7+
- Webcam
- Windows, macOS, or Linux

## Installation
1. Clone this repository or download the source code.
2. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

## Usage
1. Make sure your webcam is connected.
2. Run the main script:

```bash
python virtual_mouse_project.py
```

3. A window will open showing your webcam feed. Move your index finger to move the mouse. Pinch your thumb and index finger to click.
4. Press `q` to quit the application.

## Notes
- Mediapipe may require additional system dependencies. See [Mediapipe installation guide](https://google.github.io/mediapipe/getting_started/python.html) if you encounter issues.
- PyAutoGUI may require additional permissions on macOS for controlling the mouse.

## License
This project is for educational purposes.
