# A Convolutional Neural Network Based Approach for the Detection of Counterfeit Indian Currency

## Publication

This work was presented at IEEE INDISCON 2025 and published in the IEEE Xplore Digital Library.

Paper Title:
*A Convolutional Neural Network Based Approach for the Detection of Counterfeit Indian Currency*

IEEE Xplore:
https://ieeexplore.ieee.org/document/11254266

---

## Abstract

Counterfeit currency remains a significant challenge for financial systems. This project presents a deep learning based framework for detecting counterfeit Indian currency notes using MobileNet and hybrid machine learning models. The study evaluates MobileNet, MobileNet + Support Vector Machine (SVM), and MobileNet + Random Forest, comparing their effectiveness in distinguishing genuine and counterfeit banknotes.

---

## Project Overview

The primary objective of this work is to develop an automated counterfeit currency detection system using computer vision and machine learning techniques.

The following models were evaluated:

- MobileNet
- MobileNet + Support Vector Machine (SVM)
- MobileNet + Random Forest

---

## Methodology

### Data Preprocessing

- Image resizing to 224 × 224 pixels
- Pixel normalization
- Data augmentation
- Train, validation, and test split

### Model Architectures

#### MobileNet

A lightweight convolutional neural network designed for efficient image classification.

#### MobileNet + SVM

MobileNet is used for feature extraction, while SVM performs classification.

#### MobileNet + Random Forest

MobileNet generates feature embeddings which are classified using a Random Forest model.

---

## Results

| Model | Accuracy |
|---------|---------|
| MobileNet | 97% |
| MobileNet + Random Forest | 92% |
| MobileNet + SVM | 90% |

The MobileNet model achieved the highest overall performance.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- Scikit-Learn
- MobileNet
- OpenCV
- NumPy
- Matplotlib

---

## Repository Structure

```text
.
├── dataset/
├── README.md
├── notebooks/
├── models/
└── results/
```

## Authors

Bhoomika Mudi  
Harshavardhini Sumasri Muppavarapu  
Jahnavi Naga Srija Sandrana  
Jahnavi Sai Sri Kaka  
Mekala Ratna Raju  

SRM University AP, India

---

## Future Work

- EfficientNet based architectures
- Transfer learning enhancements
- Larger datasets
- Real-time deployment
- Mobile application integration

---

## Citation

If you use this work, please cite the corresponding IEEE publication.
