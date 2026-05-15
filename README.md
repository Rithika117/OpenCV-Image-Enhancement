# OpenCV-Image-Enhancement
Histogram equalization is used to improve the contrast and brightness of an image. For grayscale images, it is applied directly to pixel intensity values. For color images, the image is converted from BGR to HSV, and equalization is applied only to the V channel. This improves image brightness without changing the original colors.
## Aim
To write a Python program using OpenCV to perform histogram equalization on both grayscale and color images in order to enhance the contrast, brightness, and visual quality of the image.
## Software Required
Anaconda – Python 3.7
Jupyter Notebook / VS Code
OpenCV
NumPy
Matplotlib
## Simple Steps 
  1)Import OpenCV, NumPy, and Matplotlib.
  2)Read the image in grayscale format.
  3)Display the grayscale image.
  4)Draw the histogram for the grayscale image.
  5)Apply histogram equalization to improve contrast.
  6)Display the enhanced grayscale image and its histogram.
  7)Read the same image in color format.
  8)Convert the color image from BGR to HSV.
  9)Apply histogram equalization only on the V channel.
  10)Convert the image back from HSV to BGR.
  11)Display the original and enhanced color images.
  12)Compare the histograms before and after equalization.
  ## Output:
The output shows the original image and its histogram first. After applying histogram equalization, the enhanced image is displayed. The enhanced image looks brighter, clearer, and has better contrast than the original image. The histogram after equalization is more spread out, which shows that the pixel intensity values are improved.
<img width="1357" height="917" alt="image" src="https://github.com/user-attachments/assets/490c30f8-1445-415c-8f05-60a5213a0b36" />
<img width="1425" height="928" alt="image" src="https://github.com/user-attachments/assets/dd87ace6-2924-43f2-b13c-cab8a893a9f5" />

## result:
Thus, histogram equalization is successfully performed on both grayscale and color images using OpenCV. The contrast and brightness of the images are significantly improved, enhancing visual quality and feature visibility.
