# Customer-Churn-Prediction-using-Machine-Learning

Customer Churn Prediction is a Machine Learning project that predicts whether a telecom customer is likely to leave the service or continue using it. The project includes data preprocessing, exploratory data analysis, handling class imbalance using SMOTE, training multiple machine learning models, and building a Hybrid Voting Classifier for improved prediction performance.

---

## Project Overview

This project helps telecom companies identify customers who are likely to churn so that appropriate customer retention strategies can be applied.

---

## Dataset

Dataset: Telco Customer Churn Dataset

- Total Records: 7043
- Features: 20
- Target Variable: Churn (Yes/No)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- Pickle

---

## Machine Learning Models

- Decision Tree
- Random Forest
- XGBoost
- AdaBoost
- Hybrid Voting Classifier (Random Forest + XGBoost)

---

## Features

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Label Encoding
- Handling Class Imbalance using SMOTE
- Model Training
- Cross Validation
- Hybrid Voting Classifier
- Model Saving using Pickle
- Customer Churn Prediction

---

## Project Workflow

1. Load the dataset.
2. Clean and preprocess the data.
3. Perform exploratory data analysis.
4. Encode categorical variables.
5. Split the dataset into training and testing sets.
6. Apply SMOTE to balance the classes.
7. Train multiple machine learning models.
8. Perform 5-fold Cross Validation.
9. Build a Hybrid Voting Classifier.
10. Evaluate the model.
11. Save the trained model and encoders.
12. Predict churn for new customer data.

---

## Project Structure

```text
Customer-Churn-Prediction/
│
├── adaboost_customerchurn.py
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── customer_churn_model.pkl
├── encoders.pkl
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

Move to the project directory

```bash
cd customer-churn-prediction
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Run the project

```bash
python adaboost_customerchurn.py
```

---

## Required Libraries

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
imbalanced-learn
xgboost
```

---

## Model Evaluation

The models are evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- 5-Fold Cross Validation

---

## Sample Prediction

Example Input

- Gender: Female
- Senior Citizen: No
- Contract: Month-to-Month
- Monthly Charges: 29.85
- Total Charges: 29.85

Example Output

```text
Prediction: Churn
Probability: [[0.32, 0.68]]
```

---

## Future Improvements

- Hyperparameter Tuning
- Feature Selection
- Stratified K-Fold Cross Validation
- Flask or FastAPI Deployment
- Streamlit Web Application
- Docker Support
- Cloud Deployment

---

## Author

Raj

B.Tech in Computer Science and Engineering

Machine Learning | Python | Data Science

---

## License

This project is intended for educational and learning purposes.
