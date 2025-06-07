1) Dataset :
Source: https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance?resource=download
File: student_habits_performance.csv
Features: study_hours_per_day, sleep_hours
Target: exam_score

2) Data Visualization :
A scatter plot is created to observe the relationship between study hours and exam score.
A linear regression line is plotted to visualize the model's predictions.

3) Model Training :
A Linear Regression model is trained using:
X = perform[["study_hours_per_day", "sleep_hours"]].values
Y = perform[["exam_score"]].values
model.fit(X, Y)
The model attempts to find the best linear relationship between the inputs (X) and the target (Y).

4) Model Evaluation :
Mean Squared Error (MSE): 84.84
R² Score: ~0.448
This indicates that the model explains about 44.8% of the variance in exam scores.

5) Output Plot :
Blue Dots: Actual data points
Red Line: Model’s predicted trend line
A grid is included for readability.

6) How to Run :
Open the notebook in Google Colab.
Upload student_habits_performance.csv (download from the Kaggle link above).
Run all cells to see visualizations and evaluation metrics.

7) License :
This project is licensed under the MIT License — feel free to use or modify it for educational purposes.

