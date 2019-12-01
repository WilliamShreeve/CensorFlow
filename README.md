# CensorFlow

CIS365 Project 3. William Shreeve, Ben Townsend, Parker Petroff, Grant Ivernsen

## Required Libraries
`numpy`

`tensorflow==1.15` or `tensorflow-gpu==1.15`

`pillow`

`opencv-python`

## Instructions

### Static Image Testing

To test a static image, place it in the static_test_image directory. Then, run the following command in the root of the project directory:

`python test_static_img.py <image_name>`

A window will appear and will box any 'flipping of the bird' if detected.

### Webcam Gesture Detection

To test the object detection model on a live feed, simply run the following command in the root of the project directory:

`python webcam_censor.py`

This will pick the first webcam feed available on the machine this code is ran on and show a live feed. If a middle finger is detected, it will box the object and display the certanity of the gesture.
