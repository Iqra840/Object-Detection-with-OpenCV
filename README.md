# Object-Detection-with-OpenCV
Detecting objects using the Python library OpenCV without providing training data

The following code detects objects by detecting countours in the image. The first part of the code segments an object into grey portions using a threshold, and then marks the area of these thresholds so that they appear as discrete units.

Next, we introduce our test image, which is a peach. 


![Alt Text](https://github.com/Iqra840/Object-Detection-with-OpenCV/blob/master/img.png)


The code converts the RGB value of the image into the HSV value, and we assign ranges to these values so the code detects spaces which are within this range. The following image is the result of this detection.
![Alt Text](https://github.com/Iqra840/Object-Detection-with-OpenCV/blob/master/img1.png)

The final part of the code detects the largets contour. This is important because there may be noise in the background which the code might accidently pick up as being the object. We therefore want to select the largest contour.
