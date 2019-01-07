# kmeans-for-lossy-data-compression
This short code uses the k-means algorithm from the sklearn library in order to compress the size of images. 
This code can also be seen as a simple example of image segmentation.

Each pixel has 3 colors dimensions (Red, Green, Blue), all the pixels of the image are the training set.
Each color has 8 bit precision (from 0 o 255). 

In a first time k-means are computed among all the pixels (also called centroids). Then, in a second time, each pixel of the input image is assigned to its closest centroid.

With such an algorithm, the number of colors used in a picture can be significantly reduced. It can be also useful for image segmentation.

![Example of pictures compression with different numbers of k-means (10, 5, 2)](https://github.com/matpich94/kmeans-picture-compression/edit/master/picture_compression.jpg)
