# Student Performance Analysis & Prediction using Machine Learning

## Project Description
This project analyzes student performance data and uses Machine Learning to predict a student's average academic score based on demographic and educational factors.
The project covers the complete Data Science workflow, including data analysis, visualization, Machine Learning, model evaluation, feature importance, and an interactive Gradio application.

## Project Objectives
- Analyze student performance data.
- Perform exploratory data analysis and visualization.
- Build Machine Learning models to predict average student scores.
- Evaluate the models using MAE, MSE, and R².
- Identify important features using Random Forest.
- Create an interactive Gradio application for predictions.
-
## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Gradio
- Jupyter Notebook

- ## Dataset
-The dataset contains information about 1,000 students.

### Features
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

### Created Features
- Average Score
- Performance Category

## Exploratory Data Analysis
The dataset was explored to understand student performance patterns.

The analysis included:
- Dataset structure and information
- Missing-value checking
- Descriptive statistics
- Average score analysis
- Gender-based performance comparison
- Test preparation analysis
- Subject-wise score comparison
- Score distributions
- Relationships between subjects
- Correlation analysis
- Feature importance visualization

## Machine Learning
Two Machine Learning models were developed:

1. Linear Regression — used as the baseline model.
2. Random Forest Regressor — used as the improved model.

### Model Development
- Selected relevant features.
- Applied One-Hot Encoding to categorical features.
- Split the dataset into 80% training and 20% testing data.
- Trained the models.
- Generated predictions on the test data.

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

These metrics were used to compare the baseline Linear Regression model with the Random Forest model.

## Interactive Gradio Application

An interactive web application was created using Gradio.

The application allows users to enter student information and receive:

- Predicted Average Score
- Performance Level

This provides a simple interface for testing the trained Machine Learning model.

## Conclusion

This project demonstrates an end-to-end Data Science workflow, from data analysis and visualization to Machine Learning and deployment.

A Random Forest model was developed to predict student average performance, and an interactive Gradio application was created to make the model easy to use.

This project provides practical experience with Python, data analysis, visualization, Machine Learning, and model deployment.

## Project Files

- `Student_Performance_Analysis.ipynb` — Main Jupyter Notebook
- `student_performance_random_forest.pkl` — Trained Random Forest model
- `student_performance_random_forest_encoder.pkl` — Feature encoder
- `Student_Performance_Analyzed.csv` — Analyzed dataset
- `Feature_Importance.csv` — Feature importance results
- `Student_Performance_Project_Summary.txt` — Project summary
## How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Open `Student_Performance_Analysis.ipynb` in Jupyter Notebook.
4. Run the notebook cells from top to bottom.
5. Run the Gradio application to make predictions.

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib gradio
