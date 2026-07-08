# Speech-Based-COPD-Detection

## Project Pipeline

```mermaid
flowchart TD
    A[Speech Recordings]
    B[Audio Preprocessing]
    C[Feature Extraction - OpenSMILE eGeMAPS]
    D[Feature Selection - RFE]
    E[Machine Learning Models]
    F[SVM Linear and RBF]
    G[Random Forest]
    H[COPD Prediction]
    I[Performance Evaluation]

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    E --> G
    F --> H
    G --> H
    H --> I
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
