# Cardio Vascular Disease Detection System

This project demonstrates the use of the **XGBoost** classifier to predict the likelihood of cardiovascular disease based on various health indicators such as age, gender, blood pressure, cholesterol levels, and lifestyle habits.

The system is built using **Python** and **XGBoost**, with a focus on preprocessing the data, training the model, and allowing users to input their data for real-time predictions.

## Key Features:
- **Data Preprocessing**: Clean and transform raw data, including feature engineering.
- **Model Training**: Utilize **XGBoost** to build a highly accurate prediction model.
- **User Input**: Accept user inputs for personalized cardiovascular risk prediction.
- **Model Evaluation**: Evaluate performance with accuracy score, confusion matrix, and classification report.

## Technologies Used:
- **XGBoost** for Gradient Boosting.
- **Scikit-learn** for data manipulation and evaluation metrics.
- **Pandas** and **NumPy** for data handling.
- **Matplotlib** and **Seaborn** for data visualization.

---

## Dataset

The dataset used contains medical records of individuals and their associated risk factors such as:

- Age, Gender
- Blood Pressure (Systolic and Diastolic)
- Cholesterol Levels, Glucose Levels
- Lifestyle habits: Smoking, Alcohol consumption, Physical activity

The dataset is preprocessed to remove missing values, normalize features, and split into training and test sets.

---

## Model Building

The model is built using **XGBoost**. Below are the steps followed:

1. **Data Loading and Preprocessing**: Clean and prepare the dataset.
2. **Feature Selection**: Select important features like age, blood pressure, and cholesterol levels.
3. **Model Training**: Train the XGBoost model on the training data.
4. **Model Evaluation**: Test the model performance using a test dataset and evaluate metrics like accuracy, confusion matrix, and classification report.

---

## User Input for Prediction

The system allows users to input their details to make personalized predictions:

- Age, Gender, Height, Weight
- Blood Pressure (Systolic and Diastolic)
- Cholesterol Levels, Glucose Levels
- Smoking, Alcohol consumption, Physical activity

The inputs are scaled and used to predict the likelihood of cardiovascular disease.

---

## Evaluation



After training the model, it is evaluated using:

- **Accuracy**: Measures overall performance.
- **Confusion Matrix**: Provides insight into the model's true positives and negatives.
- **Classification Report**: Detailed metrics like precision, recall, and F1-score.

Model achieved **84.4% accuracy** on the test set.

---

## Usage Instructions

1. Run the model and load the dataset:


2. To make predictions for a new user, input their details when prompted:

    - Age, Gender, Height, Weight
    - Blood Pressure, Cholesterol Levels, Glucose Levels
    - Lifestyle habits (Smoking, Alcohol, Activity)

3. The system will output whether the user is likely to have cardiovascular disease based on the inputted data.

---

## Conclusion

This project provides an efficient cardiovascular disease detection system using **XGBoost**. The model processes medical data and enables real-time predictions for users, empowering early detection of heart-related issues.

Feel free to fork this project, and contribute by making pull requests!

---


