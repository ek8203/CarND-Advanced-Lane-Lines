
### Sefl-Driving Car Nanodegree Program. Term 1
<img style="float: left;" src="https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg">

## Project 4: Advanced Lane Finding

### Overview
---
The goal of this project is to create a software pipeline to identify the lane boundaries in a video from a front-facing camera on a car.

The project includes following procedures:
* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

A detail witeup of the projects can be found in [writeup_report.md](writeup_report.md) document.

### Project directory content:

* [README.md](README.md) - This file.
* [advanced_lane_finding.ipynb](advanced_lane_finding.ipynb) -  The actual project code with the solution.
* [writeup_report.md](writeup_report.md) - The project writeup - a markdown file that includes the rubric points as well as description of how each point was addressed in the project.
* [project_video_output.mp4](project_video_output.mp4) - The output video of the lane boundaries and numerical estimation of lane curvature and vehicle position.
* *`camera_cal/`* - A folder with the input and output images for camera calibration
* *`ouput_images/`* - A folder with examples of the output from each stage of the processing pipeline 

### Project Environment

The project environment was created with [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit).
