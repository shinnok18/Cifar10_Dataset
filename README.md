# CIFAR-10 Dataset Model Evaluation

## Introduction
This project aims to evaluate the performance of various machine learning and deep learning models using the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 color images, each with a size of 32x32 pixels, categorized into 10 different classes. The models are assessed using metrics such as accuracy, precision, recall, F1-score, and ROC AUC.

## Models and Their Performance
### Convolutional Neural Network (CNN)
- **Accuracy:** 71%
- **Precision:** 72%
- **Recall:** 71%
- **F1-Score:** 71%
- **ROC AUC:** 96%

### K-Nearest Neighbors (KNN)
- **Accuracy:** 34%
- **Precision:** 46%
- **Recall:** 32%
- **F1-Score:** 33%

### Logistic Regression
- **Accuracy:** 37%
- **Precision:** 37%
- **Recall:** 37%
- **F1-Score:** 37%
- **ROC AUC:** 79%

### Decision Tree
- **Accuracy:** 27%
- **Precision:** 27%
- **Recall:** 27%
- **F1-Score:** 27%
- **ROC AUC:** 60%

### Random Forest
- **Accuracy:** 48%
- **Precision:** 48%
- **Recall:** 48%
- **F1-Score:** 48%
- **ROC AUC:** 86%

### LightGBM
- **Accuracy:** 53%
- **Precision:** 53%
- **Recall:** 53%
- **F1-Score:** 53%
- **ROC AUC:** 90%

### XGBoost
- **Accuracy:** 54%
- **Precision:** 54%
- **Recall:** 54%
- **F1-Score:** 54%
- **ROC AUC:** 90%

### CatBoost
- **Accuracy:** 45%
- **Precision:** 44%
- **Recall:** 45%
- **F1-Score:** 45%
- **ROC AUC:** 86%

### Gradient Boosting Machine (GBM)
- **Accuracy:** 34%
- **Precision:** 34%
- **Recall:** 34%
- **F1-Score:** 34%
- **ROC AUC:** 75%

### Support Vector Machines (SVM)
- **Accuracy:** 54%
- **Precision:** 54%
- **Recall:** 54%
- **F1-Score:** 54%
- **ROC AUC:** 90%

## Evaluation Metrics
For each model, accuracy, precision, recall, and F1-score were calculated. ROC AUC scores were also included to provide a broader perspective on classification performance.

## Results and Discussion
The experimental results indicate that the CNN and SVM models generally outperformed the others, especially in terms of ROC AUC scores, highlighting their superior classification capabilities. Simpler models, like the Decision Tree, showed poor performance, struggling to handle more complex data structures.

## Conclusion
This project compares the performance of various machine learning and deep learning algorithms on the CIFAR-10 dataset, highlighting the strengths and weaknesses of each model. The findings can guide model selection for data science applications.
