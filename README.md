# Explainable AI – Student Performance Predictor

This project uses a Decision Tree Classifier to predict student performance based on:

- Attendance (%)
- Study Hours per Day
- Internal Marks

## Model Output Example

![Output](output.png)

## Technologies Used

- Python
- Scikit-learn
- NumPy
- Google Colab

## Model Explanation

The Decision Tree provides explainable rules such as:

- If Attendance ≤ 65 → At Risk
- If Attendance > 65 and Study Hours ≤ 3.5 → Pass
- If Attendance > 65 and Study Hours > 3.5 → Distinction

This makes the model transparent and easy to interpret.

![Model Output](output.png)

