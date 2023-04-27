# Photo Straightener
A Python program using OpenCV that unskews an image using automated edge and corner detection. It works by using a median blur along with Canny edge detection to find the edges and corners of the image, before narrowing them down to the "true corners" which are used to unskew the image. It is primarily designed for straightening text written on paper, but will work on most quadrilateral subjects as well.

Goole Colaboratory link: https://colab.research.google.com/drive/1ZgBPczKO6FexqKxAm188VBJC2mYid1EW
