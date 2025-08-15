# RetailGenius
⚡ A smart retail analytics and demand forecasting tool using machine learning to optimize inventory decisions.


This project provides insights into retail inventory trends and builds predictive models to forecast demand. It utilizes Python-based data science tools and techniques to help retail businesses make informed inventory decisions.

---

## 📁 Project Structure

```
.
├── Retail_Inventory_Analysis_and_Demand_Forecasting.ipynb
├── README.md
├── requirements.txt             # (List of all required Python packages)
└── retail_store_inventory.csv  # (Place your CSV or data files here)


```

---

## 🧠 Objectives

- Analyze sales, inventory, and demand patterns.
- Forecast future product demand using machine learning.
- Understand the effect of promotions, discounts, weather, and seasonality.
- Assist in making data-driven restocking and pricing decisions.

---

## 📦 Dataset Features

The dataset contains ~73,000 rows with the following sample columns:

- `Date`
- `Store ID`
- `Product ID`
- `Category`
- `Region`
- `Inventory Level`
- `Units Sold`
- `Units Ordered`
- `Demand Forecast`
- `Price`
- `Discount`
- `Weather Condition`
- `Holiday/Promotion`
- `Competitor Pricing`
- `Seasonality`

---

## 🧰 Tools & Libraries Used

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Seaborn & Matplotlib
- XGBoost
- LightGBM
- Jupyter Notebook

---

## ⚙️ Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature engineering (time features, lag features)

2. **Exploratory Data Analysis (EDA)**
   - Visualizing trends and patterns
   - Correlation heatmaps

3. **Model Building**
   - Linear Regression
   - Random Forest Regressor
   - XGBoost Regressor
   - LightGBM Regressor

4. **Model Evaluation**
   - RMSE, MAE, R² Score
   - Cross-validation

---

## 📈 Results

- **Demand Prediction Accuracy**: The model was able to predict demand with an acceptable level of accuracy.
- **Advanced Models**: Models like XGBoost and LightGBM outperformed basic linear models.
- **Key Features**:
  - `Units Sold`
  - `Price`
  - `Discount`
  - `Seasonality`
  - `Holiday`

### Models Built for Demand Forecast

1. **Model 1 - Linear Regressor**
   - **Mean Absolute Error (MAE)**: 28.72
   - **Mean Squared Error (MSE)**: 1342.30
   - **R² Score**: 0.8771

2. **Model 2 - Bayesian Regressor**
   - **Mean Absolute Error (MAE)**: 7.46
   - **Mean Squared Error (MSE)**: 74.38
   - **R² Score**: 0.9932

3. **Model 3 - Gradient Boosting**
   - **Mean Absolute Error (MAE)**: 7.82
   - **Mean Squared Error (MSE)**: 84.58
   - **R² Score**: 0.9923

4. **Model 4 - Random Forest**
   - **Mean Absolute Error (MAE)**: 7.65
   - **Mean Squared Error (MSE)**: 79.92
   - **R² Score**: 0.9927

---

## 🚀 Future Work

- Integrate real-time demand prediction using APIs.
- Deploy the model as a Flask app.
- Add automatic alerts for low inventory.

---

## ✍️ Authors

- Team Leader : Abhilash Surapuchetty
- Team Members: Abhilash Surapuchetty , Yadala Venkata Siva Surya , Satya Sai Ramesh , Naganna Dora Sastry and Somanaboina Nandish.

---

## 📄 License

This project is for academic and learning purposes only.

## 📬 Contact Us

Feel free to reach out for collaboration, queries, or feedback!

- **📧 Email**: [alash0849@gmail.com](mailto:alash0849@gmail.com)  
- **🔗 LinkedIn**: [Abhilash Surapuchetty](https://www.linkedin.com/in/abhilash-surapuchetty-baa0a4267/)
