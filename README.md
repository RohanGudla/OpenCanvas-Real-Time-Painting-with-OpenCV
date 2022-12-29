# Webcam Paint Application Using Video Tracking and Finding Contours of Interest

This Python application utilizes the OpenCV library to track any blue object in the frame and uses the detected object to draw colored lines (Blue, Green, Red, and Yellow).

## Overview

Video tracking is the process of locating a moving object (or multiple objects) over time using a camera. To achieve video tracking, this project employs an algorithm that analyzes sequential video frames to determine the movement of targets between the frames.

There are two major components of a visual tracking system:

1. **Target Representation and Localization:** This aspect involves representing the target object and localizing it within each frame of the video.

2. **Filtering and Data Association:** Here, the system filters out noise and associates data between frames to track the object accurately.

## Dependencies

To run this project, you will need the following dependencies:

- Python
- OpenCV
- numpy
- deque (collections)

## Execution

To execute the project, run the following command:

```bash
python main.py
```

## Project Report

For more detailed information, you can refer to the [Project Report](https://bit.ly/ProjectReportsOfTanishqWadhwani).

If you find this side project helpful in your journey, please consider giving it a star. Your support would be greatly appreciated!

Wishing you all the best in your endeavors!