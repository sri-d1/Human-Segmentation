
# Human Segmentation using U-Net

## Overview
This repository focuses on human segmentation using the U-Net architecture, a convolutional neural network well-suited for semantic segmentation tasks. Human segmentation has applications in various fields, such as video editing, virtual reality, and human-computer interaction.

## Table of Contents  
- [Introduction](#Introduction)
- [Language and Libraries](#language-and-libraries )
    - [Language](#language)
    - [Libraries](#libraries)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [License](#license)




## Introduction
Human segmentation involves delineating human figures from the background in images or videos. The U-Net architecture, with its contracting and expansive paths, is particularly effective for this task.

## Language and Libraries
#### Language : Python
#### Libraries : Tensorflow, Numpy, Matplotlib

## Usage
The code is built on Google Colab on an iPython Notebook.
```bash
Download the repository, upload the notebook and dataset on colab, and execute!
```

## Dataset
UP-3D data set is used for this project. More specially UP-S31 containing 8515 images divided as images and masks.
Dataset link : https://files.is.tuebingen.mpg.de/classner/up/#datasets

For Project purpose 1501 images and masks were used after uploading to google drive. Below directory structure was used:

- Data 
    - Images
    - Masks

## Model Architecture
U-Net is a convolutional neural network architecture designed for semantic segmentation. It consists of a contracting path, a bottleneck, and an expansive path. The architecture is symmetrical, and the expansive path mirrors the contracting path, which helps in capturing context at multiple scales.

## Results
Below are the images showing Predicition , Ground Truth and Actual Image 


## License
[MIT](https://choosealicense.com/licenses/mit/)








