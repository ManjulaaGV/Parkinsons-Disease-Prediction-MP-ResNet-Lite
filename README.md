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

<img width="330" height="470" alt="Accuracy" src="https://github.com/user-attachments/assets/9b789786-f502-45db-b807-2de9784be02a" />


Precision

<img width="302" height="226" alt="prec" src="https://github.com/user-attachments/assets/5f01e46c-6c83-4e66-84f8-cade7de5c95b" />


Recall

<img width="301" height="224" alt="recall" src="https://github.com/user-attachments/assets/08028a8f-f56d-4cd7-8ae1-3fd3ebb6a895" />


F1-Score

<img width="294" height="219" alt="f1score" src="https://github.com/user-attachments/assets/d398bc2b-248e-4e8e-83dc-48a3563a2fab" />

ROC-AUC

<img width="361" height="269" alt="rocauc" src="https://github.com/user-attachments/assets/ee51ed0d-39a6-40dd-b38a-07414c2dcc06" />


🔹 Model Architecture

<img width="350" height="594" alt="model_architecture" src="https://github.com/user-attachments/assets/ffec2cf7-164b-4041-a487-0ce8db787aa5" />


🔹 Performance Comparison

<img width="552" height="338" alt="model comparison" src="https://github.com/user-attachments/assets/c13baa92-107a-46d6-82b6-677325bfd40f" />


 Interpretability

SHAP analysis confirms the diagnostic importance of key acoustic biomarkers such as HNR, Jitter, Shimmer, RPDE, and PPE, supporting clinical transparency.

 Applications

Early-stage PD screening

Telehealth-based monitoring

AI-assisted neurological diagnostics

Author

Manjulaa G V

SRM Institute of Science and Technology
