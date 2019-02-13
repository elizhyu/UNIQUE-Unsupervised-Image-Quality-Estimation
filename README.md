# UNIQUE-Unsupervised-Image-Quality-Estimation

This is a demonstration of the algorithm described in the paper ["UNIQUE: Unsupervised Image Quality Estimation"](https://ghassanalregibdotcom.files.wordpress.com/2016/10/temel2016_spl1.pdf). Given an original and a distorted image, UNIQUE gives out a score 
that approximates the perceptual quality of the distorted image. The score lies between 0 and 1 (1 being the best quality).

You can change this program as you like and use it anywhere, but please refer to its original source (cite our paper and our web page at
https://ghassanalregib.com/unique-unsupervised-image-quality-estimation/).

### Usage :

Run the demo.m file. 

### ABSTRACT 

In this paper, we estimate perceived image quality using sparse representations obtained from generic image databases through an unsupervised learning approach. A color space transformation, a mean subtraction, and a whitening operation are used to enhance descriptiveness of images by reducing spatial redundancy; a linear decoder is used to obtain sparse representations; and a thresholding stage is used to formulate suppression mechanisms in a visual system. A linear decoder is trained with 7 GB
worth of data, which corresponds to 100,000 8x8 image patches randomly obtained from nearly 1,000 images in the ImageNet 2013 database. A patch-wise training approach is preferred to maintain local information. The proposed quality estimator UNIQUE is tested on the LIVE, the Multiply Distorted LIVE, and the TID 2013 databases and compared with thirteen quality estimators. Experimental results show that UNIQUE is generally a top performing quality estimator in terms of accuracy, consistency, linearity, and monotonic behavior.

### UNIQUE : UNSUPERVISED IMAGE QUALITY ESTIMATION

The learnt filter weights and the results of the algorithm :

<img style="float: right;" src="/Images/Visualization.png">  


![UNIQUE Filters](/Images/Visualization.png)
![Results Filters](/Images/Results.png)


Paper : [PDF](https://ghassanalregibdotcom.files.wordpress.com/2016/10/temel2016_spl1.pdf)  
Citation : [Bib](https://ghassanalregibdotcom.files.wordpress.com/2016/10/can_spl2016-bib.zip)


