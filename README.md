# PREDICTION OF CRITICALLY ILL PATIENTS’ CONDITION AND SURVIVAL, HOSPITALIZED, AND NON-HOSPITALIZED DEATH
Fatality prediction in Support2 dataset using machine learning techniques like: ensemble model random forest plus feed forward neural network, hybrid with logical regression, MLP, random forest model, decision tree, SVM, logistic regression, naive bayes.

## INTRODUCTION
Fighting a life threating disease is difficult, but so is the decision making of whether you want to go 
through the treatment phase without knowing how it will end. This is why it would be very useful to find 
a way to predict the survival rate and the difficulties a patient will go through if they decide to take on the 
treatment process. This is the aim of Support2 dataset. It is a dataset containing two study phases in 
different time periods of 1905 individual critically ill patients with one or more of the nine disease 
categories: acute respiratory failure, chronic obstructive pulmonary disease, congestive heart failure, liver 
disease, coma, colon cancer, lung cancer, multiple organ system failure with malignancy, and multiple 
organ system failure with sepsis. The goal is to determine these patients' 2- and 6-month survival rates 
based on several physiologic, demographics, and disease severity information. It is an important problem 
because it addresses the growing national concern over patients' loss of control near the end of life. It 
enables earlier decisions and planning to reduce the frequency of a mechanical, painful, and prolonged 
dying process. The objective of this study is to develop and validate a prognostic model that estimates 
survival over a 180-day period for seriously ill hospitalized adults (phase I of SUPPORT) and to compare 
this model's predictions with those of an existing prognostic system and with physicians' independent 
estimates (SUPPORT phase II)

## METHODOLOGY 
This project focuses on predicting three target values (sfdm2, hospitalized deaths, death) in the Support 2 
dataset using supervised learning techniques. The workflow includes:

1. **Data Manipulation**: Feature normalization techniques such as Min-Max normalization and ZScore normalization, are applied to enhance the dataset.
2. **Model Training**: sfdm2 Prediction (MLP, Hybrid): MLP and Hybrid models are trained with 
varying architectures for optimal performance. Hospitalized Death Prediction (Decision Trees, 
Logistic Regression, Naive Bayes): Decision trees and logistic regression models are explored 
with different parameters. Death Prediction (Decision Trees, Random Forest, SVM): Naive 
Bayes, SVM and random forest models are implemented for death prediction.
3. **Testing and Model Evaluation**: Model performance is assessed using test data, with accuracy 
metrics calculated to identify top-performing models.
