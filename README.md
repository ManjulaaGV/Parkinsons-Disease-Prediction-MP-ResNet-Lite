Parkinson’s Disease Detection using Hybrid ML–DL Framework
MP-ResNet-Lite with Voice Biomarkers



This repository accompanies the research manuscript titled:

“Parkinson’s Disease Detection Using Hybrid ML-DL Voice Biomarkers and Projection-Residual Networks”

 Overview

This repository presents a hybrid Machine Learning and Deep Learning framework for early detection of Parkinson’s Disease using non-invasive voice biomarkers from the UCI Parkinson’s dataset.

The proposed system integrates classical ensemble learning with a lightweight custom neural architecture — MP-ResNet-Lite — designed for small medical datasets.

 Methodology
 
  1️. Feature Engineering

Domain-driven composite voice biomarkers were extracted, including:

Jitter–Shimmer Ratio

Tremor Severity Index

Harmonic–Noise Composite

Voice Quality Score

These features capture vocal instability and dysphonia characteristics associated with Parkinson’s Disease.

  2️. Machine Learning Pipeline

Optimized Weighted Ensemble (RF + XGBoost + SVM + LR)

Adaptive SMOTE for class imbalance

SHAP-based model interpretability

  3️. Deep Learning Model – MP-ResNet-Lite

A lightweight custom neural network with:

Dense acoustic representation layers

Projection-based compression

Residual-style feature refinement

Dropout regularization

Sigmoid binary classifier

Designed for stability, generalization, and clinical feasibility.

 Performance

MP-ResNet-Lite outperformed classical ML baselines across key metrics:

Accuracy

Precision

Recall

F1-Score

ROC-AUC

🔹 Model Architecture

🔹 Performance Comparison

🔹 Sample Predictions

 Interpretability

SHAP analysis confirms the diagnostic importance of key acoustic biomarkers such as HNR, Jitter, Shimmer, RPDE, and PPE, supporting clinical transparency.

 Applications

Early-stage PD screening

Telehealth-based monitoring

AI-assisted neurological diagnostics

Author

Manjulaa G V

SRM Institute of Science and Technology
