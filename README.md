# Sales Forecasting Using Linear Regression

## Project Overview

This project predicts future monthly sales using the Linear Regression algorithm. Historical sales data is preprocessed and transformed into a supervised learning problem using lag features, allowing the model to forecast future sales trends.

The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, prediction, and visualization.

---

## Dataset

**Dataset:** Store Item Demand Forecasting Dataset

The dataset contains historical sales information with the following features:

- Date
- Store ID
- Item ID
- Sales (Target Variable)

The dataset was aggregated into monthly sales before training the model.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

1. Load the dataset
2. Data preprocessing
3. Convert dates to datetime format
4. Aggregate monthly sales
5. Perform Exploratory Data Analysis (EDA)
6. Transform the time series into supervised learning data
7. Scale the data using MinMaxScaler
8. Train the Linear Regression model
9. Predict future sales
10. Compare Actual vs Predicted Sales

---

## Machine Learning Model

- Linear Regression

---

## Results

The Linear Regression model successfully captured the overall trend of monthly customer sales. The predicted sales closely followed the actual sales during the testing period, demonstrating the model's ability to forecast future sales patterns.

---

## Repository Structure

```text
Sales-Forecasting-Using-Linear-Regression
│
├── Sales_Forecasting.ipynb
├── train.csv
└── README.md
```

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/Lakshay-Kapoor-OG/Sales-Forecasting-Using-Linear-Regression.git
```

### Install the required libraries

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

### Run the notebook

```bash
jupyter notebook Sales_Forecasting.ipynb
```

Open the notebook and run all the cells sequentially.

---

## Future Improvements

- Implement Random Forest Regression
- Implement XGBoost Regression
- Build an LSTM model for time-series forecasting
- Deploy the model using Streamlit

---

## Author

Lakshay Kapoor
