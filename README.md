# Median-Filtering-in-Image-Processing
Using Median filtering to reduce salt and pepper noise in an image

Median filtering is a nonlinear operation often used in image processing to reduce "salt and pepper" noise.

Median filtering is a nonlinear process useful in reducing impulsive, or salt-and-pepper noise. It is also useful in preserving edges in an image while reducing random noise. Impulsive or salt-and pepper noise can occur due to a random bit error in a communication channel. In a median filter, a window slides along the image, and the median intensity value of the pixels within the window becomes the output intensity of the pixel being processed.For example, suppose the pixel values within a window are 5,6, 55, 10 and 15, and the pixel being processed has a value of 55. The output of the median filter an the current pixel location is 10, which is the median of the five values.

Like lowpass filtering, median filtering smoothes the image and is thus useful in reducing noise. Unlike lowpass filtering, median filtering can preserve discontinuities in a step function and can smooth a few pixels whose values differ significantly from their surroundings without affecting the other pixels.
