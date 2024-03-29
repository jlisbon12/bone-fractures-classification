# Detecting Bone Fractures Utilizing Res-Net Variants

## Introduction

This project, developed at Kennesaw State University's Department of Computing & Software Engineering, leverages the power of Residual Networks (ResNet) and deep learning to enhance the detection and classification of bone fractures from X-ray images. Our aim is to improve the diagnostic process in orthopedic medicine, making it faster, more accurate, and less reliant on human interpretation.

## Project Objectives

  - Develop and validate a deep learning model utilizing ResNet architectures to accurately detect and classify bone fractures in X-ray images.
  - Compare the performance of various ResNet variants to identify the most effective model.
  - Evaluate the clinical applicability of the models and their potential to streamline the diagnostic process in orthopedic care.

## Dataset

The FracAtlas dataset, comprising approximately 14,068 X-ray images, forms the backbone of our project. Sourced from three distinct medical centers, this dataset includes a diverse array of fracture types, ensuring our models' robustness and applicability across varied scenarios. All images were preprocessed to comply with ethical standards, maintaining patient confidentiality and data integrity.

## Methodology

We employed various ResNet models (ResNet-18, ResNet-34, ResNet-50, ResNet-101, and ResNet-152), optimizing them for the task of fracture detection. Key steps in our methodology included:

  - Data preprocessing, including image resizing, normalization, and augmentation, to prepare the dataset for model training.
  - Model training and validation, using a 70-20-10 split for train-validation-test datasets.
  - Performance evaluation based on accuracy, sensitivity, specificity, and diagnostic efficacy.

## Results

Our findings indicate that ResNet-34 provides an optimal balance between complexity and performance, showcasing superior accuracy and efficiency in fracture detection compared to other variants. Detailed results, including comparative analysis and performance metrics, are available in the Results section.
