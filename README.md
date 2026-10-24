# Student Placement Prediction Using Machine Learning

## 📌 Project Overview

This project uses supervised Machine Learning classification algorithms to predict whether a student will be placed based on academic and personal features.

The project implements three classification algorithms and compares their performance using various evaluation metrics.

## 🎯 Objective

To build and evaluate Machine Learning models that predict student placement outcomes based on features such as age, CGPA, internships, history of backlogs, gender, hostel status, and academic stream.

## 🤖 Algorithms Implemented

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

## 📂 Dataset Features

The dataset contains student information, including:

- Age
- Internships
- CGPA
- Hostel
- History of Backlogs
- Gender
- Stream
- PlacedOrNot (target variable)

**Target Variable:**
- `0` — Not Placed
- `1` — Placed

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Pickle

## ⚙️ Project Workflow

1. Load the placement selection dataset.
2. Perform data preprocessing and one-hot encoding.
3. Split the dataset into training and testing sets.
4. Apply feature scaling where appropriate.
5. Train classification models.
6. Tune model hyperparameters using GridSearchCV.
7. Evaluate model performance.
8. Save trained models using Pickle.
9. Predict placement outcomes for new student inputs.

## 📊 Model Evaluation

The models are evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-score
- Cross-validation accuracy during hyperparameter tuning

### Logistic Regression

- Test Accuracy: **81%**
  
### K-Nearest Neighbors (KNN)

- Test Accuracy: **75**

### Gaussian Naive Bayes

- Test Accuracy: **44**

*Note: Model performance depends on the dataset, train-test split, preprocessing, and hyperparameter settings. The reported results should correspond to the final version of the code.*



## 💾 Model Deployment

The trained models are saved using Python's Pickle module so they can be loaded later for predictions without retraining.

For Logistic Regression and KNN implementations that use feature scaling, save the scaler along with the classifier and apply the same transformation to new inputs.

**Security note:** Only load Pickle files from trusted sources.

## 📈 Key Learnings

- Understanding supervised Machine Learning classification.
- Comparing different classification algorithms.
- Performing data preprocessing and feature encoding.
- Applying feature scaling.
- Tuning hyperparameters using GridSearchCV.
- Evaluating classification models with multiple metrics.
- Saving trained models and making predictions on new data.

## 🔮 Future Improvements

- Compare additional classification algorithms, such as Random Forest and Decision Tree.
- Improve model performance through further experimentation.
- Use cross-validation for more reliable evaluation.
- Build a simple web application for interactive placement prediction.
- Explore feature importance and model interpretability.

## 👨‍💻 Author

Sowmiya

LinkedIn: www.linkedin.com/in/sowmiya-s-70546b275
## ⭐ Acknowledgement

This project was developed as a practical exercise in Machine Learning classification, model evaluation, and deployment using Python and Scikit-learn.
