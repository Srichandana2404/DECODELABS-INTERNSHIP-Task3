# DECODELABS-INTERNSHIP-Task3
🏢 HR Analytics – Employee Attrition Prediction
📂 Dataset Overview
File: 10_HR_comma_sep.csv

Type: HR analytics dataset containing employee information.

Key Features:

Salary (categorical: low, medium, high)

Department (e.g., sales, technical, support, HR, etc.)

Left (binary target: 1 = employee left, 0 = stayed)

Other HR-related attributes (e.g., satisfaction level, number of projects, average monthly hours, tenure).

🎯 Project Objective
The goal of this project was to predict employee attrition (whether an employee leaves the company) using HR data.
This is a classification problem, where the target variable is left.

⚙️ Steps Performed
Data Exploration

Checked for missing values and categorical distributions.

Explored attrition patterns across salary levels and departments.

Visualizations

Countplot (Salary vs Left) → Shows attrition trends across salary categories.

Countplot (Department vs Left) → Highlights departments with higher attrition rates.

Modeling

Applied machine learning classification models.

Best-performing model achieved an accuracy score of 82%.

Evaluation

Compared predictions with actual attrition values.

Used metrics like accuracy, precision, recall, and F1-score.

📊 Results
Model Accuracy: 82%

Insights from Visualizations:

Employees with lower salaries showed higher attrition rates.

Certain departments (e.g., sales, support) had higher turnover compared to technical roles.

These findings can help HR teams design better retention strategies.

🚀 How to Run
bash
# Clone repository
git clone <your-repo-link>

# Install dependencies
pip install -r requirements.txt

# Run the script
python hr_attrition_prediction.ipynb

📈 Visualizations
Countplot (Salary vs Left) → Attrition patterns by salary category.

Countplot (Department vs Left) → Department-wise attrition comparison.

📝 Conclusion
The model achieved 82% accuracy in predicting employee attrition.

Salary and department are strong indicators of whether employees are likely to leave.

Future improvements could include:

Testing ensemble methods (Random Forest, XGBoost).

Feature engineering (e.g., combining satisfaction level with workload).

Using SMOTE or class balancing techniques if attrition classes are imbalanced.
