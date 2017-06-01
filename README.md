# **Self Driving Car Udacity Assignment 1 (Lane Tracking** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

Input Image:
------------
<img src="test_images/solidWhiteCurve.jpg" width="480" alt="Combined Image" />

Output Image:
------------
<img src="test_images_output/solidWhiteCurve.jpg" width="480" alt="Combined Image" />

Flow of the Pipeline:
---------------------
1. Convert Color to Black & White Image
2. Canny edge detector to detect edges
3. Hought transform to find lines
4. Extrapolation of lines using and finding two lines left and right line for the line
