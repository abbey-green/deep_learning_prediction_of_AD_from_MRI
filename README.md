# Deep learning-based detection of Alzheimer’s disease from MRI scans and enhanced interpretability with Grad-CAM

T1-weighted magnetic resonance imaging (MRI) provides high-resolution snapshots of the brain that have been widely used for Alzheimer’s disease (AD) diagnosis. Recent advancements in deep learning approaches have shown promise in improving MRI-based AD diagnosis, yet it remains unclear whether brain structure differences commonly found in AD are relevant to model performance. Additionally, current models rely on volumetric analysis of the hippocampal region (Marcisz et al., 2023), which is computationally expensive and requires considerable time to train. To address the high computational cost and limited interpretability of current models, we trained a 3-layer convolutional neural network model on 2D slices of 3D MRI images from 1) AD and 2) Healthy Control (HC) groups using a dataset from Alzheimer's Disease Neuroimaging Initiative (ADNI). We evaluated the model’s predictive accuracy on a validation and test set followed by an assessment of both the area under the receiver operating characteristic curve (AUC) and F1 score. To assess which features are relevant to the deep learning model prediction, we used Grad-CAM (Gradient-weighted Class Activation Mapping), which identifies regions relevant to the classification decision. The model resulted in a classification accuracy of 73.5% and 66.2% for validation and test sets respectively, with an AUC of .801 and F1 of .73 on the test set. Grad-CAM results suggest that ventricle areas contribute to classification of AD.
