# Bank Personal Loan Prediction

## Project Overview
This project was part of my midterm exam for the Deep Learning course in my 4th semester. The objective was to develop a predictive model that determines whether a personal loan application should be approved or rejected. The bank provided customer data, including demographic details, account information, and transaction history, which was used to build a binary classification model. The goal is to classify each loan application as either "accepted" or "rejected" based on the likelihood of repayment. This helps the bank make more accurate lending decisions, reducing risk while improving customer service.

## Dataset
The dataset, provided by the lecturer, contains demographic and financial information about the bank's customers. It includes various features such as credit score, age, balance, and tenure, which serve as inputs to predict whether a customer is likely to repay a personal loan.

## Model Architecture
We were tasked with creating our own model architecture and then introducing modifications to improve it. The performance of both models was compared to assess which one better predicted personal loan approval.

## Evaluation Metrics
Since this is a binary classification problem, we evaluated the models using Precision, Recall, F1-score, and Accuracy. Special focus was placed on the F1-score due to the class imbalance in the dataset, where a majority of customers were not granted personal loans.

## Results
![Model 1 Results](https://github.com/user-attachments/assets/a5b994a5-0343-4dbe-9051-d49ff1430096)
![Model 2 Results](https://github.com/user-attachments/assets/b8e3d658-7726-420e-8691-30cef2cd1adc)

After comparing both models, **Model 2** demonstrated better overall performance in predicting personal loan approval for this bank, particularly in terms of the F1-score, which is crucial given the class imbalance.
