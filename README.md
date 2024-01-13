
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

 ![Unknown](https://github.com/sri-d1/Human-Segmentation/assets/68694495/46c40a46-565a-4619-8333-796cd2949426)

![image](https://github.com/sri-d1/Human-Segmentation/assets/68694495/8f8009db-2295-47a4-97a7-6e88dd6142b8)


 


## Model Architecture
U-Net is a convolutional neural network architecture designed for semantic segmentation. It consists of a contracting path, a bottleneck, and an expansive path. The architecture is symmetrical, and the expansive path mirrors the contracting path, which helps in capturing context at multiple scales.
![image](https://github.com/sri-d1/Human-Segmentation/assets/68694495/981b12d4-71a4-4625-bbbc-3cffb22ed530)

## Results
Below are the images showing Predicition , Ground Truth and Actual Image 
![image](https://github.com/sri-d1/Human-Segmentation/assets/68694495/964e33a2-64f6-45ed-a6dd-168108a6e66a)

Predicted results were good for normal background subjects, and poor result was generated for image with complex background(3rd image). Results can be improved by training more data and fine tuning the results.


## License
[MIT](https://choosealicense.com/licenses/mit/)








