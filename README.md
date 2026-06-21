# scikit-learn Cookbook

## Code Reproduction + Theoretical Deep Dive

### Author
**Sulthon Arif Imadudin**  
S1 Teknik Komputer - Telkom University

### Course
Machine Learning Enrichment Assignment

### Reference Book
**scikit-learn Cookbook (Third Edition)**  
Chris Albon  
O'Reilly Media

---

# Repository Overview

This repository contains code reproduction, chapter summaries, theoretical explanations, and practical implementations based on the book **scikit-learn Cookbook**.

The purpose of this project is to strengthen understanding of Machine Learning concepts and practical implementation using Python and the Scikit-Learn library.

Each chapter includes:

- Chapter Summary
- Theoretical Explanation
- Code Reproduction
- Practical Examples
- Chapter Conclusion

---

# Topics Covered

## Chapter 1 - Common Conventions and API Elements

Topics:

- Estimator
- Transformer
- Predictor
- Pipeline
- Scikit-Learn API

Implementation:

- Linear Regression
- StandardScaler
- Pipeline Workflow

---

## Chapter 2 - Pre-Model Workflow and Data Preprocessing

Topics:

- Data Cleaning
- Missing Values
- Standardization
- Normalization
- One-Hot Encoding

Implementation:

- SimpleImputer
- StandardScaler
- MinMaxScaler
- OneHotEncoder
- ColumnTransformer

---

## Chapter 3 - Dimensionality Reduction Techniques

Topics:

- Dimensionality Reduction
- PCA
- LDA
- t-SNE

Implementation:

- Principal Component Analysis
- Linear Discriminant Analysis
- t-SNE Visualization

---

## Chapter 4 - Nearest Neighbors Methods

Topics:

- K-Nearest Neighbors
- Distance Metrics
- Hyperparameter Selection

Implementation:

- KNN Classification
- GridSearchCV
- Model Evaluation

---

## Chapter 5 - Linear Models and Regularization

Topics:

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet

Implementation:

- Regression Modeling
- Regularization Techniques
- Hyperparameter Optimization

---

## Chapter 6 - Logistic Regression

Topics:

- Binary Classification
- Multiclass Classification
- Probability Prediction

Implementation:

- Logistic Regression
- Confusion Matrix
- Classification Report
- ROC-AUC

---

## Chapter 7 - Support Vector Machines

Topics:

- Support Vector Machine
- Hyperplane
- Margin
- Kernel Trick

Implementation:

- Linear Kernel
- RBF Kernel
- Grid Search Optimization

---

## Chapter 8 - Trees and Ensemble Methods

Topics:

- Decision Trees
- Random Forest
- Gradient Boosting
- AdaBoost

Implementation:

- Tree-Based Models
- Ensemble Learning
- Model Comparison

---

## Chapter 9 - Working with Text Data

Topics:

- Natural Language Processing
- Bag of Words
- TF-IDF
- Text Classification

Implementation:

- CountVectorizer
- TfidfVectorizer
- Logistic Regression for Text

---

## Chapter 10 - Clustering Methods

Topics:

- K-Means
- Hierarchical Clustering
- DBSCAN
- Silhouette Score

Implementation:

- Unsupervised Learning
- Cluster Evaluation
- Cluster Visualization

---

## Chapter 11 - Outlier Detection

Topics:

- Isolation Forest
- Local Outlier Factor (LOF)
- One-Class SVM

Implementation:

- Anomaly Detection
- Outlier Identification
- Model Comparison

---

## Chapter 12 - Cross Validation and Model Evaluation

Topics:

- K-Fold Cross Validation
- Stratified K-Fold
- Grid Search

Implementation:

- Cross Validation
- Hyperparameter Tuning
- Performance Evaluation

---

## Chapter 13 - Deploying scikit-learn Models

Topics:

- Model Persistence
- Deployment Workflow
- Production Systems

Implementation:

- Joblib
- Save Model
- Load Model
- Prediction Pipeline

---

# Libraries Used

This project utilizes the following Python libraries:

```python
numpy
pandas
matplotlib
scikit-learn
scipy
joblib
```

---

# Machine Learning Workflow

```text
Data Collection
       ↓
Data Cleaning
       ↓
Preprocessing
       ↓
Feature Engineering
       ↓
Model Selection
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Hyperparameter Tuning
       ↓
Deployment
       ↓
Monitoring
```

---

# Key Learning Outcomes

After completing this project, the following concepts were successfully studied and implemented:

### Data Preparation

- Missing Value Handling
- Feature Scaling
- Feature Encoding
- Data Transformation

### Machine Learning Models

- KNN
- Linear Regression
- Logistic Regression
- SVM
- Decision Trees
- Random Forest
- Gradient Boosting

### Unsupervised Learning

- Clustering
- PCA
- LDA
- t-SNE

### Model Evaluation

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Cross Validation

### Advanced Topics

- Pipelines
- Hyperparameter Tuning
- Outlier Detection
- Text Processing
- Model Deployment

---

# Repository Structure

```text
scikit-learn-Cookbook/
│
├── README.md
│
└── scikit-learn-Cookbook.ipynb
```

---

# Conclusion

This repository demonstrates the implementation of various Machine Learning techniques presented in the book *scikit-learn Cookbook*.

Through theoretical study and practical code reproduction, a broad range of topics were explored, including preprocessing, dimensionality reduction, supervised learning, unsupervised learning, model evaluation, text processing, anomaly detection, and deployment.

The project serves as a comprehensive practical guide for understanding how Scikit-Learn can be used to build complete Machine Learning workflows from data preparation to production deployment.

---

# References

Albon, C. (2023).

*scikit-learn Cookbook (Third Edition).*

O'Reilly Media.
