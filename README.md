# Brain Tumor MRI Classification using Custom CNN Model

This repository contains a deep learning project focused on classifying brain MRI images to detect the presence and type of brain tumors. It utilizes a custom Convolutional Neural Network (CNN) built with TensorFlow and Keras to distinguish between different tumor categories (Glioma, Meningioma, Pituitary) and images with no tumor.

## Contents

-   `brain-tumor-mri-dataset-cnn-custom-model.ipynb`: The main Jupyter Notebook containing the complete workflow for this project. This includes:
    -   Data loading and preprocessing.
    -   Custom CNN model architecture definition.
    -   Model training and validation.
    -   Model evaluation using metrics like accuracy, confusion matrix, and classification report.
    -   Prediction on new, unseen images.

## Dataset

The model was trained and evaluated using the **Brain Tumor MRI Dataset**. This dataset typically consists of MRI scans categorized into various tumor types (e.g., Glioma, Meningioma, Pituitary) and a category for 'No Tumor'. You can usually find this dataset on platforms like Kaggle.

## Requirements

To run this project, you will need Python 3.x and the following libraries:

-   `tensorflow`
-   `keras`
-   `numpy`
-   `pandas`
-   `matplotlib`
-   `seaborn`
-   `scikit-learn`
-   `Pillow` (PIL)
-   `opencv-python` (cv2)
