# Image Retreival
HW2 of Cognitive Computing, 2019 fall, NTU CSIE

## Description

In this homework, we experiment with images from 30 categories, with 20 images in each category, our goal is to design/extract features from the image and retreiveimages using the images. We experiment with color, texture/shape and local feature in this homework.

We use MAP as our evaluation metric. We do it in leave-one-out fashion and report over MAP and MAP for each category.

### Color Features

We experiment with global/local color histogram, global/local color moment and color auto-correlogram, the results are reported in hw2.ipynb

### Texture/Shape Features

We experiment with Gabor feature, local binary pattern, histogram of oriented gradient, and shape index, the results are reported in hw2.ipynb

### Local Feature

We experiment with SIFT desciptors, the result are reported in hw2.pynb

### How to run

#### Features.py / utils.py

These 2 files contain the functions for extracting feature and running experiments

#### GenerateFeatureDatabase.ipynb

This notebook would generate the feature database for exeriments, it takes pretty long to generate features, mostly spent on generating auto-correlograms, you could comment auto-correlogram out to speed up or email me to ask for the final FeatureDatabase.pkl

#### hw2.ipynb

All the experiments and results are all reported in hw2.ipynb,long with some comments and findings of the experiments.
(BTW, the tables appears to be weird on github, but looks fine when running on local jupyter notebook)

## Built With

* Python 3.7.3 :: Anaconda custom (64-bit)

## Authors

* **SaKaTetsu** - *Initial work* - [SaKaTetsu](https://github.com/SaKaTetsu)