# View Project: 

https://nbviewer.jupyter.org/github/iwasscience/KMeans_Compression/blob/master/KMeans_Compression.ipynb

# Picture Compression Project

!(cluster_error)[error.png]

In a coloured image, each pixel is of size 3 bytes (RGB), where each colour can have intensity values from 0 to 255. Image compression is a type of data compression applied to digital images, to reduce their cost for storage or transmission.

This project shows how this can be done using the KMeans Clustering technique.

Let's start by importing libraries, loading the RGB values of each pixel and displaying the image that needs to be compressed.

## Tools:

skimage, pandas, numpy, sklearn (KMeans-Clustring)

## Structure:

**- Explore original image and preprocessing**
  - load pixel (rgb-values)
  - view shape and size
  - rearange pixel dimensions for KMeans 

**- Applying KMeans-Cluestering**

- create rgb-color value centers (centroids)
- assign each pixel (rgb) the nearest centroid 

**-Conclusion/New GitHub profile picture**

- compare metrics of original image with new one
- compressed picture size is small enough to be a github profile picture


