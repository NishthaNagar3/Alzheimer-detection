## Project Objective
The primary goal of this project is to develop an early detection system for Alzheimer's Disease (AD) using machine learning and deep learning techniques. Early diagnosis is crucial for implementing timely interventions that can slow disease progression and improve patient outcomes. By analyzing various data modalities—such as MRI scans, gait patterns, and cerebrospinal fluid biomarkers—the project aims to create a robust, non-invasive, and cost-effective diagnostic tool.​

## Dataset 
This project leverages the Alzheimer MRI Preprocessed Dataset, available on Kaggle, comprising a total of 6,400 T1-weighted MRI images. Each image has been resized to 128 × 128 pixels and categorized into one of four classes, representing varying stages of Alzheimer's Disease:​
  - Non-Demented: 3,200 images
  - Very Mild Demented: 2,240 images
  - Mild Demented: 896 images
  - Moderate Demented: 64 images​
This dataset provides a balanced representation of early to moderate stages of Alzheimer's, facilitating the development of models aimed at early detection and classification of the disease.

Link to dataset-https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset

## Models used 
1. Convolutional Neural Networks (CNNs)
Custom-built CNN architectures were developed to process and classify MRI images. These models extract hierarchical features from the input data, enabling effective differentiation between various stages of Alzheimer's Disease.​

3. Principal Component Analysis (PCA) with Traditional Machine Learning Classifiers
To reduce dimensionality and highlight the most significant features from the MRI data, PCA was applied. The transformed features were then fed into traditional classifiers:​
Logistic Regression: A statistical model that predicts the probability of a categorical dependent variable.​
Support Vector Machine (SVM): An algorithm that finds the optimal hyperplane for classifying data points in high-dimensional space.​
Random Forest: An ensemble learning method that constructs multiple decision trees and outputs the mode of their predictions.​
These combinations aimed to leverage the strengths of both feature extraction and classification techniques.​

4. Transfer Learning with Pre-trained Models
Given the limited size of medical imaging datasets, transfer learning was employed using pre-trained models on ImageNet. The following architectures were fine-tuned for the Alzheimer's classification task:​
VGG16: A 16-layer network known for its simplicity and depth, effective in various image classification tasks.​
ScienceDirect
VGG19: An extension of VGG16 with three additional convolutional layers, allowing for more complex feature extraction.​
SpringerLink
ResNet50: A 50-layer deep residual network that addresses the vanishing gradient problem, enabling the training of deeper networks.​

These models were adapted to the specific nuances of MRI data, enhancing classification performance.


## Refferences 
1. https://www.inderscience.com/offers.php?id=117272
2. https://www.nature.com/articles/s41598-022-20674-x
3. https://sist.sathyabama.ac.in/sist_naac/documents/1.3.4/1822-b.e-cse-batchno-105.pdf
4. https://www.sciencedirect.com/science/article/pii/S2352914824001072
5. https://www.sciencedirect.com/science/article/pii/S1532046420301428
6. https://link.springer.com/article/10.1007/s13198-024-02441-5
7. https://github.com/shubham0730/Alzheimers-disease-detection
8. https://github.com/Nirmit1910/alzheimers-detection?tab=readme-ov-file#project-overview
9. https://github.com/sonal-bansal/Detection-and-Classification-of-Alzheimers-Disease
