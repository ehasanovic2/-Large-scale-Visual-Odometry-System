# Large-scale-Visual-Odometry-System
Final thesis of Master’s degree. Field of research is Robot Vision, Visual Odometry implemented in C++ using OpenCV library.

This thesis is about the development and implementation of a monocular visual odometry
algorithm for robot or vehical localisation. The relevance of mobile robots has distinctly
increased during the past years. For these robots it is essential to know their exact
location in the environment. Visual odometry is the method of calculating the egomotion
of one or multiple cameras, by only using the visual data provided by these cameras. In
this approach, a monocular camera is used. The line features get detected with three
different line detectors: Line Segment Detector, Standard Hough Line Transform and
Probabilistic Hough Line Transform. The algorithm will be programmed in C++ using
the computer vision library OpenCV. The results are reported on the KITTI dataset since
KITTI dataset provides information about ground truth trajectory. In the end, various
experiments are performed to determine the accuracy of the visual odometry algorithm
developed in this work.
