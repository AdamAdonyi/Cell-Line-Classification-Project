# Cell Line Classification Project


## Description
This project aims to classify 9 regularly misidentified cell lines based on microscopy images. The reason of the misclassification is the similar origin.  The goal is to distinguish between the following cell lines:

PC-3
U-251 MG
HeLa
A549
U-2 OS
MCF7
HEK 293
CACO-2
RT4

Each sample contains at least one cell and consists of 3 separate images staining different parts of the same cell:

Nucleus
Microtubules
Endoplasmic reticulum

<img src="https://github.com/AdamAdonyi/Cell-Line-Classification-Project/blob/main/Picture1.png">

## Key Features

Image preprocessing: Combining the separate images into one 3-channel image to treat samples like regular RGB images.
Data augmentation techniques to improve model performance.
Utilization of transfer learning with pre-trained models (VGG16_bn).
Model evaluation using balanced accuracy metric.
