# Medical Data Visualizer

This project analyzes medical examination data to explore the relationships between lifestyle choices, body measurements, and the presence of cardiovascular disease. Using Python data analysis and visualization libraries, the project highlights patterns in risk factors such as blood pressure, cholesterol, glucose levels, and lifestyle habits like smoking, alcohol consumption, and physical activity.

📊 Features

Data Cleaning:

Removed invalid entries (e.g., diastolic > systolic blood pressure).

Filtered extreme outliers for height and weight.

Feature Engineering:

Created an overweight indicator using BMI (Body Mass Index).

Normalized categorical features so that 0 = good and 1 = bad.

Visualizations:

Categorical Plot:

Shows the distribution of risk factors (cholesterol, glucose, smoke, alcohol, active, overweight) for patients with and without cardiovascular disease.

Correlation Heatmap:

Displays correlations between medical variables after cleaning the dataset, highlighting strong positive/negative relationships.

🛠️ Technologies Used

Python 🐍

Pandas (data manipulation)

Seaborn & Matplotlib (data visualization)

NumPy (numerical operations)

Pytest (unit testing)
