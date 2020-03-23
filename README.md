# Image Recognition Project

This project was performed as a part of the course in Machine Learning and Pattern Recognition.
The task is devoted to image recognition of colored images. Four sets of labeled images are given as input. Each picture has one object within it to be recognized.

Three different classifiers such as **kNN**, **regularized linear model** and **multi-layer perceptron** have been trained and estimated based on accuracy metric. 

Before passing the original data into any classifier, preprocessing and feature extraction have been undertaken. While doing preprocessing, PCA and SOM have been used to make an illustration of the original data in a feature space (a reduced one).  

Finally, gained results have been interpreted in terms of performance of built estimators, the pros and cons of each model have been discussed, and possible improvements in classifying images have been suggested.

## Objects to be classifed
------
* Honeycomb
<img src='http://farm2.static.flickr.com/1372/1252907196_39261195f4.jpg' width='280' height='210'>
* Bird nest
<img src='https://farm4.static.flickr.com/3384/3496787716_9b711a340a.jpg' width='280' height='210'>
* Lighthouse
<img src='http://static.flickr.com/2086/2533280415_3b239759b7.jpg' width='280' height='389'>
* Monarch butterfly
<img src='http://static.flickr.com/98/235285500_a750156f78.jpg' width='280' height='210'>

## Data
------
The images used for this project came from image database [ImageNet](http://www.image-net.org/) which provides URLs for quality-controlled and human annotated images.

In addition to three image sets provided as the default, one more extra data set of our own choice have been used. A butterfly has been chosen as an additional object to recognize.

Please head over to [data folder](/data) to have a closer look at image URLs used for this project.

## Packages used
-----
* python       3.7.3
* numpy        1.16.3
* pandas       0.24.2
* matplotlib   3.0.3
* seaborn      0.9.0
* skimage      0.15.0
* sklearn      0.20.3
* keras        2.2.4