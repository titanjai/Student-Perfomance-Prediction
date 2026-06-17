Student Performance Prediction using Machine Learning

Overview

This project predicts a student's final grade (G3) based on various academic, personal, and social factors using Machine Learning.

The objective is to analyze student-related features and build a regression model that can estimate final academic performance.

---

Dataset

The dataset contains information about students such as:

- Age
- Gender
- Family size
- Parent education
- Study time
- Absences
- Health status
- Previous grades (G1, G2)
- Other academic and personal factors

Target Variable:

- G3 (Final Grade)

Dataset Size:

- 395 Rows
- 33 Columns

---

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

---

Machine Learning Workflow

1. Data Loading

The dataset is loaded using Pandas.

2. Data Preprocessing

- Checked for missing values
- Encoded categorical features using Label Encoding
- Separated features and target variable

3. Train-Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

4. Model Training

A Linear Regression model was trained using the training dataset.

5. Prediction

The trained model was used to predict final grades on unseen test data.

6. Model Evaluation

Performance was measured using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Results:

- MAE ≈ 1.49
- MSE ≈ 5.03
- RMSE ≈ 2.24
- R² Score ≈ 0.75

---

Project Structure

student-performance-prediction/

├── Student_Performance_Prediction.ipynb

├── README.md

└── dataset.csv

---

Key Learnings

- Data preprocessing
- Label Encoding
- Train-Test Split
- Linear Regression
- Model Evaluation Metrics
- Machine Learning Workflow

---

Future Improvements

- Feature Engineering
- Cross Validation
- Hyperparameter Tuning
- Comparing Multiple Regression Models
- Deploying the model using Streamlit or Flask

---

Author

Jai Ganesh
B.Sc Artificial intelligence & Machine Learning
Machine Learning enthusiast
B.Sc Artificial Intelligence & Machine Learning

Machine Learning Enthusiast
