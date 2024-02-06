# Sales Forecast with Linear Regression Model

## Description
This project implements a sales forecasting system using a linear regression model. The goal is to predict future sales based on historical data, enabling businesses to make informed decisions and plan accordingly.

## Project Workflow

### 1. Data Preparation:
- Imported necessary libraries for data manipulation and modeling.
- Loaded the Sales Dataset.
- Checked for and handled null values in the dataset.
- Dropped irrelevant columns 'store' and 'item'.
- Converted date from object to datetime datatype.
- Aggregated sales data by month.
- Converted resulting date column to timestamp datatype.

### 2. Exploratory Data Analysis (EDA):
- Visualized sales trends over time.
- Checked for stationarity in sales data.

### 3. Model Implementation:
- Developed a linear regression model for sales prediction.
- Split the data into training and testing sets.
- Evaluated model performance.

### 4. Model Evaluation:
- Visualized predicted sales against actual sales data to assess model accuracy.

## Technologies Used
- Python
- Libraries: pandas, matplotlib, scikit-learn

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/alimustafa0/Sales-Forecast-with-Linear-Regression-Model
   ```
