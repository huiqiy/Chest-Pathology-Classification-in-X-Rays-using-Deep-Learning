# Chest Pathology Classification in X-Rays using Deep Learning

### Group: Bagel
### Nona Falaki, Junhui Li, Huiqi Yuan, Nicolai Schneider

## Contents of this folder
This folder contains the slides of the final presentation and the `ipynb` files with all the code implementations.

## GANs
The following GAN implementations can be found in this folder:
* Cycle-GAN (`CycleGAN.ipynb`)
* DCGAN (`DenseNet_VGG19_DCGAN.ipynb`)
* SRGAN (`SRGAN.ipynb`)

## Machine Learning Models
The following Machine Learning Models can be found in this folder
* __DenseNet121__ (`DenseNet_VGG19_DCGAN.ipynb`) trained on
    * Original dataset samples
    * Generated images from SRGAN
* __ResNet50__ (`Resnet50.ipynb`) trained on
   * Original dataset samples
   * Generated images from SRGAN
* __VGG-19__ (`VGG19_using_cycleGAN.ipynb`) trained on
   * Original dataset samples
   * Generated images from Cycle-GAN
* __VGG-19__ (`DenseNet_VGG19_DCGAN.ipynb`) trained on
   * Original dataset samples
   * Generated images from SRGAN

## Datasets
Our models were trained on 4 classes: __COVID-19__, __Bacterial Pneumonia__, __Viral Pneumonia__ and __Normal__ (Healthy case). The used samples were retrieved from different datasets:
* *COVID-19*: https://github.com/ieee8023/covid-chestxray-dataset
* *Bacterial Pneumonia*: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
* *Viral Pneumonia* and *Normal*: https://www.kaggle.com/tawsifurrahman/covid19-radiography-database/data

## Warning
To run the code, the datasets first need to be installed and the path to access the images has to be adjusted.
