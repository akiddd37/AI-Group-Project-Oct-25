# AI-Group-Project-Oct-25
Link to dataset: https://drive.google.com/drive/folders/1XhSfpOZ2TTkH28IbFLKq1Xz5xJN-b79g?usp=sharing
# 🐅 Animal Species Classification Project

## 📋 Project Overview
This project focuses on the application of Deep Learning to classify **10 distinct animal classes** (including Bears, Tigers, Eagles, etc.). Utilizing **Transfer Learning**, we compared the performance of three state-of-the-art Convolutional Neural Networks (CNNs) to determine the most efficient model for wildlife image classification.

This repository contains the full pipeline: **Data Collection (Web Crawling), Preprocessing, Model Training, and Evaluation.**

## 👥 Team Members
**Course:** Principle of Artificial Intelligence (ISB46703)  
**Institute:** UniKL MIIT  
**Semester:** October 2025  

| Role | Name | Student ID |
| :--- | :--- | :--- |
| **Data Engineer** | Muhamad Amirul Hakeem | 52213124031 |
| **Data Scientist** | Harith Akid | 50220124004 |
| **Data Analyst** | Muhamad Rusydi Hakim | 52213124508 |

---

## 🧠 Models & Architecture
We implemented and compared three specific CNN architectures using **Transfer Learning**:

1.  **ResNet50:** A deep residual network known for high accuracy.
2.  **DenseNet121:** A network with dense connections, efficient for feature propagation.
3.  **MobileNetV3:** A lightweight model optimized for speed and mobile deployment.

**Key Techniques Used:**
* **Transfer Learning:** Utilized ImageNet pre-trained weights (`include_top=False`).
* **Metrics:** Evaluated using Accuracy and mAP (Mean Average Precision).

---

## 📂 Dataset
* **Source:** Web Crawling (Bing Image Downloader)
* **Total Images:** ~9,700 images
* **Classes:** 10 (Bear, Deer, Eagle, Elephant, Fox, Horse, Monkey, Owl, Parrot, Tiger)
* **Split Ratio:** * Train: 70%
    * Validation: 20%
    * Test: 10%

---

## 📊 Results Summary

| Model | Test Accuracy | Test mAP Score | Training Time (50 Epochs) |
| :--- | :--- | :--- | :--- |
| **ResNet50** | 0.9791 | 0.9941 | 20 minutes |
| **DenseNet121** | 0.9781 | 0.9974 | 21 minutes |
| **MobileNetV3** | 0.9652 | 0.9936 | 11 minutes |

*Detailed Confusion Matrices and Loss/Accuracy graphs are available in the notebooks.*

---



