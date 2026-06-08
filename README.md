# Hand Gesture Recognition using OpenCV and MediaPipe

This project is a real-time hand gesture recognition system using a webcam. It uses **OpenCV** for video capture and display, and **MediaPipe** for detecting and analyzing hand landmarks. The system identifies how many fingers are raised and classifies simple hand gestures from 0 to 5 fingers.

## Features

* Real-time webcam-based hand tracking
* Detection of 21 hand landmarks
* Finger state identification
* Gesture classification from 0 to 5 fingers
* Visual feedback with annotations on the video stream
* Simple and beginner-friendly Python implementation

## Technologies Used

* Python
* OpenCV
* MediaPipe
* NumPy

## How It Works

The system captures video frames from the webcam using OpenCV. MediaPipe detects the hand and identifies 21 landmarks on the hand. Based on the position of each finger landmark, the system determines whether each finger is open or closed.

After identifying the finger states, the system counts the number of raised fingers and classifies the gesture. For example, showing two fingers can be classified as a peace gesture.

## Applications

* Gesture-based user interfaces
* Touchless control systems
* Basic sign language interpretation
* Interactive games
* Human-computer interaction projects

## Requirements

Make sure you have Python installed on your system.

Install the required libraries using:

```bash
pip install opencv-python mediapipe numpy
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Praveen-0361/hand-gesture-recognition.git
```

2. Navigate to the project folder:

```bash
cd hand-gesture-recognition
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Run the Python file:

```bash
python main.py
```

## Project Structure

```bash
hand-gesture-recognition/
│
├── main.py
├── requirements.txt
└── README.md
```

## Sample Output

The webcam window will show:

* Hand landmark points
* Finger count
* Gesture label
* Real-time visual annotations

Example gestures:

* 0 fingers: Fist
* 1 finger: One
* 2 fingers: Peace
* 3 fingers: Three
* 4 fingers: Four
* 5 fingers: Open Palm

## Future Scope

* Add more complex hand gestures
* Support two-hand gesture recognition
* Improve accuracy in different lighting conditions
* Control system volume, media, or mouse cursor
* Integrate with sign language recognition
* Build a GUI-based application

## Author

**Praveen Kumar Reddy Anduri**
