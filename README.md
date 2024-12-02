# 🔬 Cell Line Classification: Microscopy Image Analysis

## 📝 Project Overview

This advanced machine learning project tackles a critical challenge in biomedical research: accurately classifying tumor cell lines using microscopy imaging techniques. By leveraging deep learning and advanced image processing, we aim to address the persistent issue of cell line misidentification.

## 🎯 Project Objectives

- Develop a robust machine learning model to classify 9 challenging cell lines with high precision
- Demonstrate the power of multi-channel image processing in biological image classification
- Create a generalizable approach for distinguishing between closely related cell lines

## 🧬 Cell Lines Studied

| Cell Line | Cancer Origin | Tissue Type |
|-----------|---------------|-------------|
| PC-3 | Prostate Cancer | Epithelial |
| U-251 MG | Glioblastoma | Glial |
| HeLa | Cervical Cancer | Epithelial |
| A549 | Lung Carcinoma | Epithelial |
| U-2 OS | Osteosarcoma | Bone |
| MCF7 | Breast Cancer | Epithelial |
| HEK 293 | Embryonic Kidney | Epithelial |
| CACO-2 | Colorectal Adenocarcinoma | Epithelial |
| RT4 | Bladder Cancer | Epithelial |

## 🖼️ Image Preprocessing Methodology

### Multi-Channel Image Composition
Our unique approach combines three grayscale images representing different cellular compartments:

1. **Nucleus Channel**: Structural foundation
2. **Microtubules Channel**: Cellular infrastructure
3. **Endoplasmic Reticulum Channel**: Cellular processing network

#### Image Transformation Example
![Multi-Channel Image Transformation](https://github.com/AdamAdonyi/Cell-Line-Classification-Project/blob/main/Picture1.png)

## 🤖 Technical Approach

### Key Technical Components
- **Image Preprocessing**: Custom multi-channel image merging
- **Data Augmentation**: Techniques to enhance model generalizability
- **Transfer Learning**: Utilizing pre-trained VGG16_bn architecture
- **Evaluation Metric**: Balanced accuracy for robust performance assessment

### Preprocessing Pipeline
- Merge 3 grayscale images into a single RGB representation
- Apply advanced data augmentation
- Normalize image features
- Prepare dataset for deep learning model

### Model Architecture
- Base Model: VGG16 (Batch Normalization variant)
- Fine-tuned for multi-class cell line classification
- Handles nuanced differences between similar cell lines


