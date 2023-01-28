# camera_matrix
This repository simulates camera matrix using Python
Following tasks are demonstrated in the notebook:

Generation of a set of at least 100 random points on a randomly-oriented 3D plane, and visualizing that the generated points are indeed on a plane.
Setting up of two arbitrary camera matrices.
Computation of the image coordinates of the 3D points on the plane using these cameras.
Calculation of the homography between image points using the cv2.findHomography function.
Visualization of that the two images are related by a homography by comparing the transformed points and the original points and by plotting the two images and the points .
The code in this repository is useful for understanding the basic concepts of camera projection, camera matrix, derivation of homography between two cameras, rotation, translation in 2D and 3D, and how to use the cv2.findHomography function. It can be used as a reference for computer vision and image processing projects.
