# Autism Prediction Age-Wise Analysis Using Machine Learning

This project aims to predict autism spectrum disorder (ASD) across different age groups using various machine learning models. By leveraging data-driven insights and classification algorithms, the model evaluates patterns and attributes that may indicate a higher probability of autism.

##  Project Overview

Autism spectrum disorder is a developmental disorder that affects communication, behavior, and social skills. Early detection and intervention can significantly improve the quality of life of individuals with ASD. This project focuses on:

1. Classifying individuals into autistic or non-autistic categories.
2. Performing analysis across various age groups.
3. Enhancing model accuracy using feature selection and preprocessing.

## 📁 Dataset

The dataset used is an augmented version that combines multiple publicly available autism screening datasets, covering:

1. **Children**
2. **Teenagers**
3. **Adults**

### Features include:

1. Age
2. Gender
3. Ethnicity
4. Family history of autism
5. Screening question answers (A1 to A10)
6. Result score
7. Communication issues
8. Behavioral symptoms
9. Others

## 🧰 Tech Stack

1. **Python**
2. **Pandas, NumPy** – Data processing
3. **Seaborn, Matplotlib** – Data visualization
4. **Scikit-learn** – Machine learning algorithms
5. **XGBoost** – Gradient boosting model
6. **Jupyter Notebook / Google Colab** – Experimentation

## ⚙️ ML Models Used

1. K-Nearest Neighbors (KNN)
2. Decision Tree
3. Random Forest
4. Logistic Regression
5. Tuned XGBoost
6. Naive Bayes
7. Support Vector Classifier (SVC)
8. Gradient Boosting
9. AdaBoost
10. MLP classifier
11. LDA

## 📊 Evaluation Metrics

1. Accuracy
2. Precision
3. Recall
4. F1-Score
5. Confusion Matrix

## 🧪 Process Flow

1. Data Collection & Augmentation
2. Data Cleaning & Preprocessing
   (i) Handling missing values
   (ii) Label encoding
   (iii) Normalization
3. Exploratory Data Analysis
   (i) Distribution across age groups
   (ii) Correlation analysis
4. Model Training & Tuning
5. Age-Wise Performance Evaluation
6. Model Selection

## 🔍 Results

1. Age-wise classification helps in tailoring interventions and early detection.
2. Random Forest and XGBoost models showed the highest accuracy.
3. Performance varied across age groups, underlining the importance of personalized datasets.

## 📌 Conclusion

The project demonstrates how ML can assist in autism detection based on behavioral and demographic attributes. It further emphasizes the need for age-specific models and personalized screening methods.

## 🏁 Future Work

1. Include deep learning models for better pattern recognition.
2. Use larger, more diverse datasets.
3. Integrate with clinical decision support systems.



