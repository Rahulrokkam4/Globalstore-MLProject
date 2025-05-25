# Globalstore-MLProject
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

  <h1>📊 Global Super Store - Profit Prediction</h1>

  <h2>🎯 Project Objective</h2>
  <ul>
    <li>The Global Super Store dataset contains 24 features including sales, profits, customer, and product details.</li>
    <li>The goal of this project is to predict profits for future sales transactions based on features like product category, shipping mode, region, and discount.</li>
  </ul>

  <h2>🛠️ Technologies & Methods Used</h2>

  <h3>📌 Data Preprocessing</h3>
  <ul>
    <li><strong>Handling Missing Values:</strong> Checked for nulls and imputed or removed them appropriately.</li>
    <li><strong>Feature Engineering:</strong> Created new features like <code>Total Profit = Profit - Shipping Cost</code>.</li>
    <li><strong>Encoding Categorical Variables:</strong> Applied label encoding to convert categories into numerical format.</li>
    <li><strong>Outlier Handling:</strong> Used the IQR (Interquartile Range) method to remove outliers.</li>
    <li><strong>Data Scaling:</strong> Standardized numerical columns using standard scaling to improve model performance.</li>
  </ul>

  <h3>📈 Model Selection & Training</h3>
  <ul>
    <li><strong>Linear Regression:</strong> Used as a baseline model.</li>
    <li><strong>Decision Tree Regressor:</strong> Captured non-linear relationships but overfitted slightly.</li>
    <li><strong>Random Forest Regressor:</strong> Improved generalization and accuracy.</li>
    <li><strong>XGBoost Regressor:</strong> Delivered the best performance with feature importance insights.</li>
  </ul>

  <h2>📊 Model Evaluation</h2>
  <ul>
    <li>Metrics used: <strong>Mean Absolute Error (MAE)</strong>, <strong>Mean Squared Error (MSE)</strong>, and <strong>R² Score</strong>.</li>
    <li><strong>XGBoost</strong> achieved the lowest MAE & MSE values, indicating superior predictive performance.</li>
  </ul>

  <h2>⚠️ Challenges & Solutions</h2>
  <ul>
    <li><strong>Outliers:</strong> Handled using the IQR method to ensure model robustness.</li>
    <li><strong>Overfitting:</strong> Mitigated using cross-validation techniques during training.</li>
  </ul>

  <h2>✅ Conclusion</h2>
  <p>This project demonstrates a full machine learning workflow on a real-world dataset. By applying preprocessing, feature engineering, model training, and evaluation, we successfully built a robust regression model that can predict future profits accurately.</p>

</body>
</html>
