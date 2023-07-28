I. What is Hand Gesture based Volume Control application?
---------------------------------------------------------
This OpenCV application allows you to control your laptop or PC's volume effortlessly using just hand gestures, like magic! No need to touch anything; the system tracks your hand movements in real-time and adjusts the volume accordingly. It works on both laptops and PCs, making it super easy to use. Enjoy the convenience of hands-free audio control with this user-friendly tool!

II. Tech Stacks
---------------
(1) OpenCV (for image processing and drawing)
(2) Mediapipe (for hand tracking)
(3) Pycaw (to link up with the system's volume)

III. Prerequisites
------------------
(1) Install Python v3.7 or higher.
(2) Download and Install the necessary packages.

IV. Features
------------
It tracks and changes the computer volume based on your hand gestures.

V. Working
----------
This project showcases the practical application of Hand Tracking technology. Once the user's hand appears in the camera, the application swiftly detects it and places a bounding box around the hand for better visibility. The system then calculates the distance between the user's index finger and thumb, and based on this, it displays the volume level using a volume bar on the screen. This innovative approach enables users to effortlessly control the volume through intuitive hand gestures.

VI. How to run this project?
----------------------------
Install Python v3.7 or above and install the necessary libraries. Now run the code in the 'hgvc.py' file using Python (preferred IDE: PyCharm).
