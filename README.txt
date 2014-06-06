Efficient Online Structured Output Learning for Keypoint-Based Object Tracking

Code to accompany the paper:
  Efficient Online Structured Output Learning for Keypoint-Based Object Tracking
  Sam Hare, Amir Saffari, Philip H. S. Torr
  Computer Vision and Pattern Recognition (CVPR), 2012

Copyright (C) 2012 Sam Hare, Oxford Brookes University, Oxford, UK

Contact: Sam Hare <sam.hare@brookes.ac.uk>

------------
Requirements
------------

OpenCV: http://opencv.willowgarage.com/
Eigen: http://eigen.tuxfamily.org/

This code has been developed and tested using 
OpenCV v2.3.1 and Eigen v3.0.1

---------
Compiling
---------

When running experiments, be sure to compile in Release mode, as Debug mode will be very slow.

-----
Usage
-----

> learnmatch [--config config-file-path]

If no path is given the application will attempt to
use ./config.txt.

Please see config.txt for configuration options.

---------
Sequences
---------

The sequences used in the paper are available to download here:

http://www.samhare.net/research/keypoints

----------------
Acknowledgements
----------------

This code makes use of the following 3rd-party code:

OpenCV graphing utilities: http://www.shervinemami.co.cc/graphs.html
BRISK: http://www.asl.ethz.ch/people/lestefan/personal/BRISK
Online Boosting: http://www.vision.ee.ethz.ch/boostingTrackers/onlineBoosting.htm
