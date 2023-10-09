# Parkinson's Disease Detection using MFCC Features

## Introduction

Parkinson's Disease (PD) is a neurological disorder affecting speech production among other functions. Early diagnosis of PD through voice analysis is of growing interest, with Mel Frequency Cepstral Coefficients (MFCC) being a prominent feature for identifying speech abnormalities in PD patients. This repository contains a study that explores the relevance of MFCC coefficients in detecting abnormal vibratory patterns indicative of Parkinson's disease during sustained vowel production.

## Dataset

The Italian Parkinson's Voice and Speech (IPVS) database is used for this study, encompassing recordings from both healthy subjects and PD patients. Data preprocessing steps are detailed in the code, including filtering, segmenting, and subsampling.

## Methodology

The study employs several machine learning algorithms, including K-Nearest Neighbors (KNN), Support Vector Machines (SVM), Decision Trees (DT), Random Forest (RF), Logistic Regression (LG), and Neural Networks, to classify PD based on MFCC features extracted from sustained vowels /a/ and /i/.

## Results

The performance of each machine learning model is evaluated in terms of precision, recall, F1-score, and accuracy for both vowel types. Results indicate the effectiveness of MFCC coefficients in distinguishing PD patients from healthy controls, with specific models showing promising results.

## Usage

You can use this repository to:

1. Explore the provided code for MFCC feature extraction and machine learning model implementation.
2. Experiment with different machine learning models or datasets for PD detection.
3. Extend the study by combining MFCC features with other descriptors or optimizing the classification process.

## Conclusion

While the accuracy rates achieved in this study are promising for the relevance of MFCC coefficients in detecting Parkinsonian dysphonia, further research and refinement of the models are needed for clinical application.
