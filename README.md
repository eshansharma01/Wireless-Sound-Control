Hand Gesture Volume Control
-----------------------------------------------------------------------------------------------
This project demonstrates a hand gesture volume control system using Python, OpenCV, MediaPipe, and Pycaw.
By leveraging computer vision and audio libraries, this system allows users to control the system volume with simple hand gestures detected through a webcam.

Features
-----------------------------------------------------------------------------------------------
Real-Time Hand Tracking: Uses MediaPipe to detect and track hand landmarks in real-time.

Gesture-Based Volume Control: Adjusts the system volume based on the distance between the thumb and index finger.

Visual Feedback: Provides visual indicators for hand landmarks and gesture detection on the webcam feed.

Smooth Integration: Utilizes Pycaw to interface with the system's audio control for seamless volume adjustment.

Dependencies
-----------------------------------------------------------------------------------------------

Python 3.x

OpenCV

MediaPipe

Pycaw

Numpy

Installation
-----------------------------------------------------------------------------------------------
Clone the repository:

git clone https://github.com/eshansharma01/Wireless-Sound-Control.git

Install the required dependencies:

pip install opencv-python mediapipe comtypes pycaw numpy

Run the script:

python hand_gesture_volume_control.py

How It Works
-----------------------------------------------------------------------------------------------
The webcam captures the video feed and processes each frame.
MediaPipe detects hand landmarks and calculates the distance between the thumb and index finger.
The system volume is adjusted based on the calculated distance, providing intuitive control through hand gestures.

Contributing
-----------------------------------------------------------------------------------------------
Contributions are welcome! Feel free to fork the repository and submit pull requests.

License
-----------------------------------------------------------------------------------------------
This project is licensed under the MIT License.
