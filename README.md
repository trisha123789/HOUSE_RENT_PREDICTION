# HOUSE_RENT_PREDICTION
🏠 House Rent Prediction

This project predicts house rents based on features like BHK, size, number of bathrooms, furnishing status, and more. It uses Exploratory Data Analysis (EDA) and a machine learning model (Linear Regression) to study and forecast rental prices.

📌 Project Workflow
1. Importing Libraries

pandas, numpy (data handling)

matplotlib, seaborn (visualization)

sklearn (ML modeling & evaluation)

2. Dataset

Dataset: House_Rent_Dataset.csv

Total Rows: 4746

Columns:

Posted On

BHK

Rent

Size

Floor

Area Type

Area Locality

City

Furnishing Status

Tenant Preferred

Bathroom

Point of Contact

3. Data Cleaning

Checked for missing values (none found).

Converted Bathroom column type.

Removed duplicate rows.

4. Exploratory Data Analysis (EDA)
🔹 Univariate Analysis

Distribution of Rent.

Outlier detection using boxplots.

🔹 Bivariate Analysis

Rent vs Size (scatter plot).

Rent vs Bathroom (scatter plot).

Rent vs BHK (boxplot).

🔹 Multivariate Analysis

Correlation heatmap between numerical features.

Pairplot for visualizing feature interactions.

5. Machine Learning Model
🔹 Data Split

Train: 80% (3796 rows)

Test: 20% (950 rows)

🔹 Model Used

Linear Regression

🔹 Evaluation Metrics

Mean Absolute Error (MAE): ~ 2.14e9

Mean Squared Error (MSE): ~ 2.14e9

R² Score (Adjusted): ~ 0.28

6. Observations

Rent is strongly influenced by Size, BHK, and Bathrooms.

Model performance (R² ~0.28) indicates Linear Regression is too simple for this dataset.

Suggestion: Try Multiple Linear Regression, Random Forest, or XGBoost for better accuracy.

📊 Visualizations

Scatter plots: Rent vs Size, Rent vs Bathrooms

Correlation heatmap

Rent distribution plot

Pairplot of numerical features

🚀 Future Improvements

Feature engineering (e.g., extract floor number, city-based encoding).

Use advanced regression models.

Hyperparameter tuning.

Deploy model using Flask/Streamlit.


⚡ Tech Stack

Python

Pandas, Numpy

Matplotlib, Seaborn

Scikit-learn
