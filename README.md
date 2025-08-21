📊LINEAR REGRESSION:

This project demonstrates how to use Linear Regression in Python with different real-world styled datasets.
The goal is to understand relationships between features (like study hours, house size, ad spend) and target values (scores, prices, sales, etc.), and to make predictions.


📌 PROJECT OVERVIEW:

Datasets used in this project:
study_hours_scores_150.csv → Predict student exam scores from study hours.

salary_experience_150.csv → Predict salary from years of experience.

house_price_multifeature_150.csv → Predict house prices based on size and bedrooms

advertising_linear_150.csv → Predict sales based on advertising spend (TV, radio, social media).



🔑KEY STEPS PERFORMED:

Loaded datasets using pandas.

Applied Linear Regression using scikit-learn.

Extracted slope(s), intercept, and R² score.

Made predictions for new data points.

(For salary dataset) Visualized regression line with matplotlib.




⚙️REQUIREMENTS:


Make sure you have the following installed:
Python 3.8+
Jupyter Notebook / any Python IDE




INSTALL DEPENDENCIES:

pip install -r requirements.txt

requirements.txt includes:
numpy
pandas
matplotlib
scikit-learn



🛠INSTALLATION AND SETUP:

Clone this repository:

git clone https://github.com/<your-username>/linear-regression-practice.git
cd linear-regression-practice


Install dependencies:

pip install -r requirements.txt

Run the scripts or Jupyter Notebook:

python study_hours_regression.py
python salary_experience_regression.py
python house_price_regression.py
python advertising_regression.py



📊OUTCOMES

1. Study Hours vs Exam Scores

Found a strong positive relationship.

Predicted score for 9 hours of study.

2. Salary vs Experience

Predicted salary for 7 years of experience.

Visualized regression line and prediction point.

3. House Price Prediction

Built multi-feature model using size (m²) and bedrooms.

Predicted price for 85 m², 3 bedrooms.

4. Advertising Spend vs Sales

Identified how each advertising channel affects sales.

Predicted sales for TV=160, Radio=32, Social=18.



🖼 OUTPUT IMAGES:

Example Salary vs Experience Regression Plot:



✅CONCLUSION:

Linear Regression works well to model relationships between variables.
R² score shows model performance (how much variance is explained).
Predictions are approximate and depend on dataset quality.


FUTURE IMPROVEMENTS:

Add more real-world features.
Try Polynomial Regression, Ridge, Lasso for better accuracy.
Use cross-validation for performance evaluation.

👩‍💻 Author

Sri Varsha P
