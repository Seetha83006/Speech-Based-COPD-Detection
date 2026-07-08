# Speech-Based-COPD-Detection

# Speech-Based COPD Detection using Machine Learning

## Project Pipeline

```mermaid
flowchart TD
    A[Speech Recordings] --> B[Audio Preprocessing]
    B --> C[Feature Extraction<br/>OpenSMILE (eGeMAPS)]
    C --> D[Feature Selection<br/>Recursive Feature Elimination (RFE)]
    D --> E[Machine Learning Models]
    E --> F[SVM (Linear & RBF)]
    E --> G[Random Forest]
    F --> H[COPD Prediction]
    G --> H
    H --> I[Performance Evaluation<br/>Accuracy • ROC-AUC • LOSO • Stratified K-Fold]
```

Machine learning approach for non-invasive COPD detection using sustained vowel speech recordings.
This project presents a non-invasive machine learning framework for Chronic Obstructive Pulmonary Disease (COPD) detection using sustained vowel speech recordings.

Features
Audio preprocessing
eGeMAPS feature extraction using OpenSMILE
Feature selection using Recursive Feature Elimination (RFE)
SVM and Random Forest classification
Stratified K-Fold and Leave-One-Speaker-Out (LOSO) evaluation
ROC-AUC based performance analysis

Tools
Python
OpenSMILE
Librosa
Scikit-learn
NumPy
Pandas

Models
Support Vector Machine (Linear & RBF)
Random Forest
Evaluation
Accuracy
ROC-AUC
Precision
Recall
F1-score
