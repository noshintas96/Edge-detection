# Edge Detection Techniques in Python

This repository contains Python code snippets for various Edge Detection techniques, including Canny edge detection, gradient calculation, Harris corner detection, and Gaussian filtering.

## Canny Edge Detection

The `Canny_detector` function implements the Canny edge detection algorithm. It performs gradient calculation, non-maximum suppression, and double thresholding to detect edges in an image. The result is displayed using matplotlib.


## Gradient Calculation

The gradient_x and gradient_y functions calculate the x and y gradients of an image using the Sobel operator. These gradients are then used for further processing, such as edge detection or feature extraction.


## Harris Corner Detection

The my_harris function implements the Harris corner detection algorithm. It computes image derivatives, calculates the response function, and applies a threshold to detect corners in an image. The result is visualized using matplotlib.


Gaussian Filtering

The gkernel and gaussianKernel2 functions generate Gaussian kernels for smoothing an image. These kernels are then convolved with the input image to perform Gaussian filtering. The smoothed image is displayed using matplotlib.
