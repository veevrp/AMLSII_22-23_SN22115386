# AMLSII_22-23_SN22115386
AMLSII Final Assignment: Image super-resolution using machine learning (SRGAN).

This repository contains works on 
[NTIRE2017 challenge](https://data.vision.ee.ethz.ch/cvl/ntire17//), image super-resolution.
There are 2 tasks on this work, A and B, which represents track 1 and track 2 from the challenge.

## Task A: Bicubic downscaling images
- uses the bicubic downscaling (Matlab imresize).

\* *Due to limited resources, it is decided to use*
- *bicubic downscaling x2 images as high resolution images. [train](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_LR_bicubic_X2.zip) / [validation](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_valid_LR_bicubic_X2.zip)* 
- *bicubic downscaling x4 images as low resolution images. [train](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_LR_bicubic_X4.zip) / [validation](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_valid_LR_bicubic_X4.zip)*

## Task B: Unknown downscaling images
- assumes that the explicit forms for the degradation operators are unknown.

\* *Due to limited resources, it is decided to use*
- *bicubic downscaling x2 images as high resolution images. [train](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_LR_bicubic_X2.zip) / [validation](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_valid_LR_bicubic_X2.zip)*
- *unknown downscaling x4 images as low resolution images. [train](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_LR_unknown_X4.zip) / [validation](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_valid_LR_unknown_X4.zip)*

## Packages
- numpy
- pillow
- matplotlib
- opencv
- tensorflow