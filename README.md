📊 Student Performance Prediction using Machine Learning
📌 Project Overview

This project focuses on predicting student final grades (G3) using various features from the Student Performance dataset. The goal is to build a regression model that can estimate a student's academic outcome based on demographic, social, and academic-related attributes.

The project explores data preprocessing, feature engineering, model building, and performance evaluation using Python and scikit-learn.

🛠️ Tech Stack & Libraries

Python

pandas → Data manipulation

matplotlib / seaborn → Data visualization

scikit-learn → Machine Learning (Linear Regression, Model Training, Evaluation, Scaling)

📂 Dataset

Source: UCI Machine Learning Repository – Student Performance Data Set

The dataset contains attributes like:

Demographics (age, gender, address, family size)

Academic information (study time, failures, absences)

Social and family background (parent’s job, family support, alcohol consumption)

Target variable: Final Grade (G3)

🚀 Project Workflow

Data Collection & Exploration

Load dataset using pandas

Check missing values, datatypes, and distributions

Feature encoding (Label Encoding / One-Hot Encoding)

Data Preprocessing

Scaling numerical features using StandardScaler

Splitting dataset into train and test sets

Model Building

Implemented Linear Regression as baseline model

Explored other ML algorithms for performance improvement

Evaluation

Accuracy Score (R²)

Mean Squared Error (MSE)

Visualization of predicted vs actual grades

📈 Results

Best Model: Linear Regression

Achieved Accuracy: ~74% (R² Score)

The model captures the relationship between input features and final grades fairly well, but further improvements are possible using advanced algorithms.

🔮 Future Improvements

Apply Ridge / Lasso Regression for regularization

Try Ensemble Models (Random Forest, Gradient Boosting)

Perform Feature Selection to reduce noise

Hyperparameter tuning with GridSearchCV

📊 Visualization Example

Scatter plot with regression line showing predictions vs actual values.

plt.scatter(y_test, y_pred, color="blue")
plt.plot(y_test, y_test, color="red", linewidth=2)  # Perfect prediction line
plt.xlabel("Actual Grades")
plt.ylabel("Predicted Grades")
plt.title("Actual vs Predicted Student Performance")
plt.show()

📌 How to Run

Clone this repository

git clone https://github.com/Lakshman Rithesh R/student-performance-prediction.git
cd student-performance-prediction


Install dependencies

pip install -r requirements.txt


Run the Jupyter Notebook / Python file

✨ Author
  Lakshman Rithesh R

🌐 LinkedIn
   www.linkedin.com/in/lakshman-rithesh-r


⚡ This project is part of my Machine Learning learning journey and showcases the application of supervised learning on real-world datasets.
