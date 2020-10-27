# SLIC Algorithm for Superpixel generation

[![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)](LICENSE.md)
---


### Author
Arpit Aggarwal


### Introduction to the Project
SLIC stands for Simple Linear Iterative Clustering. This is a method used for Superpixel generation. Superpixels help in clustering pixels of similar color and texture together and instead of working with thousands of pixels, work with superpixels can be done as pixels within the superpixel would be similar to one another on the basis of color and texture. SLIC algorithm differs from K-Means in three ways: we work with images and keep the spatial information intact, we confine pixels to be within a superpixel only if they are in a 2S x 2S area where S is a parameter and they use LAB space instead of RGB space because color distance in RGB space is not meaningful.


### Data
The dataset used is provided in notebooks folder. Five images are used on which the SLIC algorithm is tested.


### Results



### Software Required
To run the jupyter notebooks, use Python 3. Standard libraries like Numpy, OpenCV and PyTorch are used.


### Credits
The following links were helpful for this project:
1. https://medium.com/@darshita1405/superpixels-and-slic-6b2d8a6e4f08
2. https://www.groundai.com/project/superpixel-segmentation-with-fully-convolutional-networks/1
3. https://github.com/darshitajain/SLIC
