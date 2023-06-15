Certainly! Here's a sample README for the GitHub page you provided:

# Spring 2023 Final Project - Team 2

Team 2's MAE 148 Project was to replicate a mechanic in Mariokart. The car would identify a mushroom cutout, drive towards (switching lanes) and then would speed up after passing through it.

## Installation

To set up this project locally, please follow these steps:

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/UCSD-ECEMAE-148/spring-2023-final-project-team-2.git
   ```

## Contents:

1. mushroom_detection.py

The main image processing/template matching code. Takes a template image and finds the best match within an image taken by the camera and returns  its location.

2. mushroom.jpg
   
The mushroom template used in the template matching code.

3. lane_guidance_node.py

Modified lane guidance code. Includes the integrated lane switching and throttle codes that would run when the mushroom is detected.

4. lane_detection_node.py

Modified lane detection code. Includes the integrated mushroom detection code and the line/lane following code.

5. calibration_node.py

Camera Calibration Code. Used to color calibrate the Oak-D-Lite Camera.


