# Computer-Vision-2021
## Lab-1
**Q1:** Take your face image using cell phone camera or web camera.
a. Convert that into gray scale and that gray scale into binary using builtin functions and display all three in single window.
b. Find the minimum and maximum
    1.in the color image (for green, red and blue channel)
    2.in the gray scale image
    3.in the binary image
**Q2:** Write the python program which takes two polynomial as input and output the product of those two polynomials using convolution in spatial domain (in O(n^2))

## Lab-2
**Q1:** 
a.Take an image of the wall of your house and apply a sobel filter and count the number of edge pixels in the edge map 
b. Do the same operation for the image of a tree ( capture your own image of the tree ) and report your observation on the two images

**Q2:** 
Each of the images considered in the first problem apply Gaussian filters of size 7 * 7 , 9 * 9 and 11 *11. Repeat the problem 1 and report your observation

## Lab-3
**Q1:** Capture Image of chess board(in Black&amp;white) with your mobile camera. The captured image needs to be converted to gray scale and then to black and white. The binary image will look like the following. Write a python script to find all the corner points in the binary chess board image, and display integer coordinates at each corner, superimposing the coordinates with the binary image. To understand corner points, some example corner points are marked in the image given below. (0,0) needs to be displayed at topmost and left most corner, and (8,8) is to be displayed at the last corner.

## Lab-4
**Q1:** Design and implement the scheme to find the disparity map from the stereo images. Consider the following images for the test case. You are allowed to use inbuilt functions.

## Lab-5
**Q1:** Camera calibration using builtin function.

## Lab-6
**Q1:** Implement the watershed algorithm in openCV

## Lab-7
**Problem Description:**
All the images attached along with this show cells identifiable by their well-stained nuclei. The nuclei are stained either blue or brown.
The diagnosis report is defined as follows:

percentage positivity =  percentage of Total nuclei that are brown in color / Total nuclei in the picture (blue & brown inclusive)

Write a program to find the percentage of positivity in the image given below and classify into grade the level of cancer, using the thresholding scheme followed in the convention method, which is detailed below.
**The Convention Approach:**

Currently, we see the image in the microscope, count and calculate the %, manually. This is not reproducible always and is subjective. Idea is to make it objective.

The gold standard is to take prints and manually count on the images and many studies show that this is objective. To save on paper and time, we want the software to do the job. Brown nuclei indicate that they express the immune marker called Ki67 and the higher the percentage positivity, the more aggressive it is considered to be. In many cases, a cut-off is used to grade cancer. For example <15% is considered low grade and >15% as high grade. Treatment and follow-up actions differ in these 2 situations. Hence, the real problem is with borderline percentages (between 20 & 30% on manual counts). We expect the software to give more accurate and reproducible results.

Here the software must do 2 things

1) Identify percentage positivity (similar to that described above)
2) Classify the intensity of staining as low and high grade.

A score is derived based on the information from the above 2 results.

The score guides therapy and has prognostic implications too.

## Lab-8
**Q1:** Face recognition using SIFT features and the demo should be shown on students' faces.
