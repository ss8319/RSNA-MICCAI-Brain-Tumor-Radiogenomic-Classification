# RSNA-MICCAI Brain Tumor Radiogenomic Classification Kaggle Competition

To learn more about the competition and dataset see
https://www.kaggle.com/competitions/rsna-miccai-brain-tumor-radiogenomic-classification

My training notebooks utilizing Kaggle's free GPU.

# MRI Dataset
Multi-parametric MRI (mpMRI) scans, in DICOM format. The exact mpMRI scans included are:

Fluid Attenuated Inversion Recovery (FLAIR)
T1-weighted pre-contrast (T1w)
T1-weighted post-contrast (T1Gd)
T2-weighted (T2)


# Detailed Exploratory Data Analysis 
## advanced-eda-brain-tumor-data.ipynb

# Machine Learning and Deep Learning Solutions
## Brain-tumor-ml-modeling.ipynb
I explored the viability of using non-DL models in Medical Image Classification, in a field where much of the research is focused on DL models. This solution involves using a HOG descriptor to extract features and then training non-DL Classifier Models like LogisticRegression, RidgeClassifier, KNeighborsClassifier, DecisionTreeClassifier and a simple Linear Model to predict the classification.

I compared it with training on EfficientNet, a CNN DL model.


## efficientnet3d-with-one-mri-type.ipynb
Solution involves an ensemle method where each EfficientNet model is trained on 1 MRI data type and the final prediction is averaged.
