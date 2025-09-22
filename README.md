# Skin Disease Identification using Convolutional Neural Networks

## Overview
This project was completed as part of my **Final Year Project (FYP)**.  
The objective was to classify **skin diseases from dermatoscopic images** using deep learning.  
We explored different dataset preparation techniques and compared performance across **two datasets** and **two models**.  

---

## Datasets

1. **Self-Collected Dataset**
   - Images collected manually.  
   - Dataset was **augmented** using techniques such as:
   - Augmentation was crucial due to the limited number of original images.  

2. **Google Images Dataset**
   - Additional dataset curated from Google Images.  
   - Used to increase variety and size of training samples.  

---

## Models

1. **Custom CNN Model**  
   - Designed and implemented from scratch.  
   - Consists of convolutional, pooling, and dense layers.  

2. **Keras Built-in Model**  
   - Transfer learning approach using a pre-trained CNN.  
   - Fine-tuned on our datasets.  

---

## Study & Experimentation
We conducted experiments using **two datasets** and **two models**, resulting in **four combinations**:

1. Custom CNN + Self-Collected Dataset  
2. Custom CNN + Google Images Dataset  
3. Keras Pretrained Model + Self-Collected Dataset  
4. Keras Pretrained Model + Google Images Dataset  

Each combination was evaluated based on **accuracy, loss curves, and generalization ability**.  

---

## Results
- **Data Augmentation** improved the accuracy of the self-collected dataset.  
- **Transfer Learning (Keras pretrained model)** consistently outperformed the custom CNN.

---

## Project Report
The complete **FYP Report** with detailed methodology, experiments, and analysis is available in a separate repository:
https://github.com/muneebsaddal/Final-Year-Project-report/  

---
