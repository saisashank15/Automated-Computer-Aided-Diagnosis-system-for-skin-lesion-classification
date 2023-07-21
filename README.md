# Automated-Computer-Aided-Diagnosis-system-for-skin-lesion-classification

The Automated Computer-Aided Diagnosis System for Skin Lesion Classification is a project that aims to assist dermatologists and healthcare professionals in accurately classifying skin lesions as Melanoma or Benign. This system leverages image preprocessing techniques, deep learning models (such as ResNet-50 and VGG16), and an SVM classifier to achieve high accuracy in skin lesion classification.

## Key Features

- Preprocessing of Skin Lesion Images:
  - Removal of hair artifacts and unwanted elements from the image.
  - Segmentation to identify the region of interest (the skin lesion).
  - Augmentation for generating additional training data to improve model performance.

- Deep Learning Models:
  - Utilization of pre-trained ResNet-50 and VGG16 models for feature extraction.
  - Combination of features from both models to enhance classification accuracy.

- Support Vector Machine (SVM) Classifier:
  - Utilization of an SVM classifier to classify the extracted features into different skin lesion categories.
  - Training the SVM model on labeled skin lesion data to make accurate predictions.



## Preprocessing

- Hair Removal: Implement an algorithm to remove hair artifacts and other unwanted elements from skin lesion images.

- Segmentation: Utilize image segmentation techniques to isolate the region of interest (the skin lesion) from the background.

- Augmentation: Apply data augmentation techniques to generate additional training data and improve the generalization of the deep learning models.

## Deep Learning Models

- ResNet-50: Use the pre-trained ResNet-50 model to extract features from skin lesion images.

- VGG16: Use the pre-trained VGG16 model to extract features from skin lesion images.

## SVM Classifier

- SVM Model: Train an SVM classifier on the extracted features from the ResNet-50 and VGG16 models to classify skin lesions into different categories.

## Results

- Showcase the accuracy and performance metrics achieved by the automated computer-aided diagnosis system.

- Display visualizations or confusion matrices to demonstrate the system's classification performance.
