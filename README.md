# Comparative Evaluation of SDAE & 1DCNN for Breast Cancer Multi-Omics Data Classification using SVM-RFE

# Overview
This project presents a comparative evaluation of Stacked Denoising Autoencoder (SDAE) and 1-Dimensional Convolutional Neural Network (1D-CNN) for the classification of breast cancer using integrated omics data. The Support Vector Machine-Recursive Feature Elimination (SVM-RFE) method was employed for feature selection.

# Experimental Design

**Key Activities**
Data Pre-processing
• Removal of null values and missing values.

**Integration of Multi-omics**
• Concatenation-based integration using the Python library Pandas.

**Balancing Class**
• Techniques applied to ensure balanced class distribution.

**Feature Selection**
• Wrapper method applied using SVM-RFE.

**Classifier Analysis**
• Comparative analysis between Stacked Denoising Autoencoder (SDAE) and 1 Dimensional Convolutional Neural Network (1D-CNN).

**Result and Discussion**
• Detailed evaluation of classifier performance.

# Repository Structure
• data/ - Contains datasets used in the study.
• notebooks/ - Jupyter notebooks with data preprocessing, integration, and model training steps.
• models/ - Saved models for SDAE and 1D-CNN.
• results/ - Performance metrics and comparison results.
• scripts/ - Python scripts for feature selection, model training, and evaluation.
• README.md - Project overview and details (this file).

# Usage

**Data Pre-processing**
Execute the data_preprocessing.ipynb notebook to clean and prepare the data.

**Integration of Multi-omics**
Use the integration.ipynb notebook to concatenate the datasets.

**Feature Selection**
Run feature_selection.py to perform SVM-RFE and select features.

**Model Training**
Train the SDAE and 1D-CNN models using train_sdae.py and train_1dcnn.py.

**Evaluation**
Evaluate model performance using evaluate_models.ipynb.

# Results
The results of the comparative analysis will be saved in the results/ directory. Detailed discussions and insights are provided in the results_and_discussion.ipynb notebook.

# Acknowledgements
This project was completed as part of the final year project at Universiti Teknologi Malaysia. Special thanks to all who provided guidance and support throughout the project.
