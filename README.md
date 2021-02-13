# Counting-Objects-and-Identifying-Face-Pixels-in-Image
Various OpenCV algorithms used for counting the number of objects and identifying face pixels from a selfie.

# Counting the Number of Books in Image
Given an image of the bookshelf, we have to find the approximate the number of books without using any detector and only OpenCV basic algorithms.

**Approaches :
========================
1. Contours Detection with Threshold
2. Contours Detection with Threshold and Morphological Operator
3. Contours Detection with **Canny Edge Detector**

**AIM : ** To generalize the approach with other bookshelf images as well.


# Identifying Face Pixels from Selfie Image
Given an image of a selfie or an image focussed on a person, we need to identify the face pixels from the image excluding others

**Approaches :
========================
1. Clustering as Segmentation using **KMeans**
2. Segmentation based on Color Space
3. Segmentation using Texture Dectection with **Gabor Filter Bank**
4. Foreground extraction using OpenCV **Grabcut** algorithm

**AIM : ** To generalize the approach with other selfie images as well.