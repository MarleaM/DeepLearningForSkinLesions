# DeepLearningForSkinLesions

This is a repo for a project dedicated towards classifying skin lesions using machine learning models and methods.

## Contributors: 

- Adriana Cavazos (@aeacava)
- Lisa Messier (@lisamessier)
- Marlea Martens (@MarleaM)

## Problem Description

Skin lesion images present a visually rich and well-structured dataset for exploring deep learning–based image classification. In this project, we aim to develop a convolutional neural network that categorizes dermatoscopic images into several lesion classes. Our images will be split into training, validation, and test sets. Our objective is to evaluate how effectively a modern deep learning model can learn discriminative visual features in this domain and to compare its performance against baseline methods. The project will be considered successful if our model demonstrates stable learning across training and validation sets and aligns with results reported in similar machine learning studies. 

## Main Goal
Our main goal is to investigate the question: Can deep learning models accurately classify different skin lesion types from dermatoscopic images and achieve performance comparable to published baselines?

## Data
We are using the HAM10000 (“Human Against Machine with 10,000 training images”) dataset, sourced from Harvard Dataverse. The dataset includes 10,015 dermatoscopic images, 7 diagnostic categories (e.g., melanoma, nevus, benign keratosis, etc.), and metadata including patient age, lesion location, and diagnosis type.

Link to data: https://www.kaggle.com/datasets/surajghuwalewala/ham1000-segmentation-and-classification

## Note on Ethicality:
We want to emphasize that our model is intended solely as an academic exploration of deep learning methods on an existing medical dataset, not as a diagnostic tool. Any real-world application would require broader, more representative data and extensive clinical validation. Additionally, we recognize that the HAM10000 dataset underrepresents darker skin tones, which may cause a trained model to perform unevenly across diverse populations. This imbalance is a known limitation of many dermatology datasets and can introduce bias into classification results. By acknowledging these limitations, we aim to frame our work responsibly within its educational and experimental context.
