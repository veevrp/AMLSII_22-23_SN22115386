# AMLSII_22-23_SN22115386
AMLSII Final Assignment: Image super-resolution using machine learning (SRGAN, ResNet).

This repository contains works on 
[NTIRE2017 challenge](https://data.vision.ee.ethz.ch/cvl/ntire17//), image super-resolution.
There are 2 tasks on this work, A and B, which represents track 1 and track 2 from the challenge.

## Task A: Bicubic downscaling images
- uses the bicubic downscaling (Matlab imresize).
- uses jupyter notebook to solve the tasks, contained in directory A
- the images preprocessing using preprocessing.ipynb
- training ResNet using resnet_bi.ipynb
- see the result of ResNet using resnet_bi_vis.ipynb
- training SRGAN using srgan_bi.ipynb
- see the result of SRGAN using srgan_bi_vis.ipynb

### Datasets
- *high resolution images. [train](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_HR.zip) / [validation](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_valid_HR.zip)* 
- *bicubic downscaling x4 images as low resolution images. [train](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_LR_bicubic_X4.zip) / [validation](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_valid_LR_bicubic_X4.zip)*

## Task B: Unknown downscaling images
- assumes that the explicit forms for the degradation operators are unknown.
- uses jupyter notebook to solve the tasks, contained in directory B
- the images preprocessing using preprocessing.ipynb
- training ResNet using resnet_un.ipynb
- see the result of ResNet using resnet_un_vis.ipynb
- training SRGAN using srgan_un.ipynb
- see the result of SRGAN using srgan_un_vis.ipynb

### Datasets
- *high resolution images. [train](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_HR.zip) / [validation](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_valid_HR.zip)*
- *unknown downscaling x4 images as low resolution images. [train](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_LR_unknown_X4.zip) / [validation](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_valid_LR_unknown_X4.zip)*

## Packages
- numpy
- pillow
- matplotlib
- opencv
- tensorflow-gpu
