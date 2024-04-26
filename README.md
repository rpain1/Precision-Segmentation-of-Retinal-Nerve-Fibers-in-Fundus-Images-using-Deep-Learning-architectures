# Precision-Segmentation-of-Retinal-Nerve-Fibers-in-Fundus-Images-using-Deep-Learning-architectures
Deep Learning Segmentation of Retinal Fundus Images
Overview
This repository contains the implementation and evaluation of three state-of-the-art deep learning architectures for the task of segmenting retinal nerve fibers in fundus images. Our project focuses on the utilization of a hybrid U-Net with attention mechanisms, EfficientNet, and MobileNet to improve precision in medical image segmentation.

Project Description
The final project for DSCI-6011-02 DEEP LEARNING explores the efficacy of different neural network architectures in precisely segmenting retinal nerve fibers. We utilize pretrained models EfficientNet and MobileNet, known for their robustness in computer vision tasks, and enhance a U-Net architecture with attention mechanisms to focus on low-density and low-value pixel regions which are crucial for accurate medical diagnostics.

Features
Data Preprocessing: Normalization and binarization of image datasets (DRIVE and HRF) to enhance model input quality.
Model Architectures: Implementation of EfficientNet and MobileNet for base feature extraction with adaptations for segmentation tasks, and a hybrid U-Net model that incorporates attention mechanisms for enhanced segmentation precision.
Metrics for Evaluation: Models are evaluated based on accuracy, binary cross-entropy loss, and model robustness through adaptive checkpointing.
Results Visualization: Loss and accuracy graphs across training epochs, with comparative analysis of model performance.
Datasets Links
Drive Dataset: DRIVE Digital Retinal Images for Vessel Extraction
High-Resolution Fundus (HRF) Image Database: HRF Database
Usage
Detailed steps for setting up the environment, data preprocessing, model training, and evaluation are provided. This includes scripts for training models and scripts for evaluating segmentation performance using quantitative metrics.


