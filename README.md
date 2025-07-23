# ✈️ Flight-Price-Prediction-ML-Project

This project focuses on building a regression model to predict flight ticket prices using historical flight data.

## 📁 Data Source

- The dataset is a `.csv` file containing flight details and prices.
- The target variable for prediction is **`price`**.

## 🧹 Data Preprocessing & EDA

- Cleaned raw data by handling nulls and converting time columns.
- Feature engineering steps included extracting journey day/month, duration in minutes,duration category and categorizing airlines and routes.
- Exploratory Data Analysis (EDA) was performed to understand feature distributions and relationships with the target variable.

## 🛠️ Model & Evaluation

- Final model: **RandomForestRegressor**
  - `n_estimators = 300`
  - `max_depth = 10`
  - `max_features = 5`
- Evaluation Metric: **R² Score**
- Best R² Score on validation data: `0.8161`

## 🧪 Experiment Tracking

- Used **MLflow** for tracking experiments, parameters, metrics, and models.
- Tracking URI: `http://127.0.0.1:5000`
- All key model runs were logged with run names and relevant artifacts.

## 🧰 Tools Used

- Python
- Pandas, NumPy
- Scikit-learn
- Feature-engine
- XGBoost
- Matplotlib, Seaborn
- MLflow

---

Feel free to explore, run experiments, or improve the model further!
