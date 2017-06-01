# **Self Driving Car Udacity Assignment 1 (Lane Line Tracking)** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

Input Image:
------------
<img src="test_images/solidWhiteCurve.jpg" width="480" alt="Combined Image" />

Output Image:
------------
<img src="test_images_output/solidWhiteCurve.jpg" width="480" alt="Combined Image" />

Flow of the Pipeline:
---------------------
1. Adding Gaussian noise for blur effect, Convert Color to grayscale Image 
2. Canny edge detector to detect edges
3. Selecting some Region of Interest (ROI)
3. Hough transform to find lines from the detected pixels from edge detection
4. Extrapolation of lines using and finding two lines left and right line from the lines found using hough transform
