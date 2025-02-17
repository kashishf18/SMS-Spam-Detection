# SMS-Spam-Detection
A machine learning project to classify SMS messages as spam or ham (non-spam). Multiple algorithms—Naive Bayes, Logistic Regression, Random Forest, and SVM—were trained on a labeled dataset to achieve near-perfect performance.

Table of Contents
        Overview
        Dataset
        Models & Performance
        Results


Overview
This repository demonstrates a complete end-to-end pipeline for detecting spam messages:

1.Data Cleaning and Preprocessing
2.Feature Engineering with TF-IDF and custom features
3.Model Training using various classification algorithms
4.Model Evaluation using accuracy, precision, recall, F1-score, and AUC

Dataset:
       Name: spam.csv(UCI machine learning-Esther Kim) https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset


Models & Performance:
    Four main models were trained:

   Naive Bayes
   Logistic Regression
   Random Forest
   SVM
Performance:

     Random Forest Performance:
                  Accuracy: 0.99
                  AUC: 1.00
     SVM Performance:
                  Accuracy: 1.00
                  AUC: 1.00

    Naive Bayes Performance:
                 Accuracy: 0.98
                 AUC: 1.00

    Logistic Regression Performance:
                 Accuracy: 0.99
                 AUC: 1.00
Note: These results indicate that the models can effectively classify spam vs. ham messages in the given dataset.


Results
High Accuracy: Models consistently score above 98% accuracy.
AUC = 1.00 for certain models, indicating excellent discrimination ability.
Minimal False Positives/Negatives: The confusion matrix shows very few misclassifications.


