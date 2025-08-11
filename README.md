## Project Overview
This project analyzes patient data from the Cleveland Heart Disease dataset to predict the presence of heart disease using machine learning techniques. The focus is on evaluating different models and identifying the strengths and weaknesses of each, with particular attention to the K-Nearest Neighbors (KNN) algorithm.
Contributors: Jason Corona, Tyler Tseng, Raeed Shaikh, Andres Arevalo, Joshua Petrikat

## Tools
Python (Jupyter Notebook)

Pandas — Data handling

NumPy — Numerical computations

Scikit-learn — Machine learning models and evaluation

Matplotlib / Seaborn — Data visualization

## Dataset
Source: Cleveland Heart Disease dataset (UCI Machine Learning Repository)

### Features include:

Age

Sex

Chest pain type

Resting blood pressure

Cholesterol levels

Fasting blood sugar

Resting ECG results

Maximum heart rate achieved

Exercise-induced angina

Oldpeak (ST depression induced by exercise)

Slope of the peak exercise ST segment

Number of major vessels colored by fluoroscopy

Thalassemia result

### Target: Presence of heart disease (binary classification)

## Approach
### Data Preprocessing

Handling missing values

Encoding categorical variables

Normalizing numerical features

### Model Training & Evaluation

K-Nearest Neighbors (KNN)

Model selection and hyperparameter tuning

Performance evaluation using accuracy, precision, recall, and F1-score

### Findings

KNN performed well at predicting the presence of heart disease

KNN struggled to differentiate between different types of heartbeats

Highlights the importance of model choice based on task specificity

## Results Summary
### Strengths: 
KNN achieves strong results for binary classification (disease vs. no disease)

### Limitations: 
Struggles with finer-grained classification of heartbeat types

### Future Work: 
Explore models like Random Forest, SVM, or deep learning to improve heartbeat classification

## License
This project is for educational purposes using publicly available dataset.

## Acknowledgments
UCI Machine Learning Repository for providing the Cleveland Heart Disease dataset

Scikit-learn for the machine learning toolkit


