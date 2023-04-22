# Hand Gesture Volume Control
This is a Python script that uses OpenCV and HandTrackingModule to control the system volume using hand gestures. It detects hand landmarks and calculates the distance between two specific landmarks to determine the volume level. The volume level is then set using the pycaw library.

# Prerequisites
+ Python 3.x installed on your system.
- OpenCV, numpy, ctypes, and comtypes Python libraries installed.
- Webcam connected to your system.
# How to Run
- Clone the repository or download the script file to your local machine.
- Install the required libraries using the following command:
```
pip install opencv-python numpy comtypes
```
- Run the script using the following command:
```
python hand_gesture_volume_control.py
```
- Adjust the hand gestures to control the system volume. To increase the volume, bring your thumb and index finger closer. To decrease the volume, move your thumb and index finger apart.
- Press 'Esc' key to exit the program.
# Configuration
You can configure the camera resolution by uncommenting the lines # cap.set(3, wCam) and # cap.set(4, hCam) and setting the desired width and height values in pixels.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
