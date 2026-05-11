# Hotel Booking Cancellation Prediction

This project investigates the performance of several machine learning models for predicting hotel booking cancellations. The goal is to analyze how different classification models perform in identifying booking cancellations while balancing false positives and false negatives.

## Models Implemented

- K-Nearest Neighbors (KNN)
- Logistic Regression
- Naive Bayes
- Neural Network

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

## Key Findings

- Logistic Regression performed well in identifying non-cancellations but missed many actual cancellations.
- Naive Bayes achieved high recall but produced more false positives.
- KNN provided balanced overall performance.
- The Neural Network achieved the best overall performance with strong classification balance and fewer prediction errors.

## Dataset

The project uses the Hotel Booking Demand dataset containing information about hotel reservations, customer details, booking status, and cancellation records.

## Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn
