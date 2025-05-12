💎 Gemstone Price Prediction using Linear Regression
This project focuses on predicting the prices of gemstones based on various physical and categorical attributes using linear regression. It includes data cleaning, outlier handling, feature engineering, model training, and performance evaluation.

📂 Dataset
Source: gemstone.csv

Features:

Numeric: carat, depth, table, x, y, z

Categorical: cut, color, clarity

Target: price

🔍 Exploratory Data Analysis (EDA)
Checked for missing values.

Dropped unnecessary columns (id).

Analyzed feature correlation using a heatmap.

Performed Chi-square tests for feature significance (on categorical data).

Detected and visualized outliers using box plots.

🧹 Data Preprocessing
Outliers removed using IQR method.

Categorical features encoded using pd.get_dummies().

Numerical features scaled using StandardScaler.

🧠 Model Training
Algorithm: Linear Regression (Scikit-Learn)

Dataset split: 70% training / 30% testing

Features standardized before model fitting

📈 Performance Evaluation
Metrics used:

✅ Mean Absolute Percentage Error (MAPE)

✅ Mean Squared Error (MSE)

✅ Root Mean Squared Error (RMSE)

✅ R² Score

📊 Results Example
mathematica
Copy
Edit
Mean Absolute Percentage Error: 11.4%
Mean Squared Error: 210000
Root Mean Squared Error: 458
R² Score: 0.92
These results show the model performs well on the dataset with strong predictive power.

🚀 Future Work
Try more robust models like Random Forest, XGBoost, or Gradient Boosting.

Use cross-validation for better performance evaluation.

Deploy model with Flask or Streamlit for user interaction.

Save model using joblib or pickle.

🧠 Technologies Used
Python

Pandas, NumPy

Seaborn, Matplotlib

Scikit-Learn
