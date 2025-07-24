Student Performance Prediction 📚✨
This project is about predicting students' math scores using machine learning models. We cleaned the data, explored it with beautiful plots, and used different regression models to make predictions.

🔍 Dataset
We used a dataset that includes:

Gender (converted to female = 1 or 0)

Parental education

Lunch type

Test preparation

Reading and writing scores
Our goal was to predict the math score based on these features.

🧹 Data Preprocessing
Missing values were checked ✅

Categorical variables were converted using get_dummies()

Outliers were visualized using Boxplot

Data was scaled using StandardScaler

📊 Visualization
We created plots like:

Countplots (for gender, lunch, etc.)

Heatmap (correlation between scores)

Boxplots (to check outliers)

Scatterplots (actual vs predicted scores)

🤖 Models Used
We used the following models:

Linear Regression

Lasso Regression (with and without cross-validation)

Ridge Regression (with and without cross-validation)

ElasticNet Regression (with and without cross-validation)

Each model was evaluated using:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² Score

🧠 What I Learned
How to clean and prepare real-life datasets

How to visualize data clearly

How to apply regression models

How to compare model results and performance

💻 Tools Used
Python 🐍

pandas, numpy

seaborn, matplotlib

scikit-learn
