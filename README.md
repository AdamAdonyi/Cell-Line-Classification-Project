# Cell Line Classification Project


## Description
This project aims to classify 9 regularly misidentified tumor cell lines based on microscopy images. The reason of the misclassification is the similar origin - most of them endothelial cell-derived cancer cells.  The goal is to distinguish between the following cell lines

| Cell Line | Origin                |
|-----------|------------------------|
| PC-3      | Prostate cancer        |
| U-251 MG  | Glioblastoma           |
| HeLa      | Cervical cancer        |
| A549      | Lung carcinoma         |
| U-2 OS    | Osteosarcoma           |
| MCF7      | Breast cancer          |
| HEK 293   | Embryonic kidney       |
| CACO-2    | Colorectal adenocarcinoma |
| RT4       | Bladder cancer         |

Each sample contains at least one cell and consists of 3 separate images staining different parts of the same cell:


| Compartment | Origin                | type |
|-----------|------------------------|--------|
| Nucleus      | channel_1        | grey scale |
| Microtubules  | channel_2         | grey scale |
| Endoplasmic reticulum| channel_3 | grey scale |

After combining the 3 pictures per sample the following colorful result achieved:


<img src="https://github.com/AdamAdonyi/Cell-Line-Classification-Project/blob/main/Picture1.png">

## Key Features

Image preprocessing: Combining the separate images into one 3-channel image to treat samples like regular RGB images.
Data augmentation techniques to improve model performance.
Utilization of transfer learning with pre-trained models (VGG16_bn).
Model evaluation using balanced accuracy metric.
