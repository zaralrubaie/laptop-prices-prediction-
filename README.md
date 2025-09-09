# Laptop Price Prediction Using Pandas
This project predicts laptop prices based on various features using Python and Pandas. It demonstrates a complete workflow: data cleaning, preprocessing, exploratory analysis, feature engineering, and predictive modeling. The goal is to understand what drives laptop prices and build a model that can predict prices for new laptops.

## project Structure
``` 
PTOP_PRICES_PREDICTION.csv          # Main dataset containing laptop specs and prices
LAPTOP_PRICE_PREDICTION_SUMMARY.txt # Text summary explaining analysis and insights
laptop-prices-prediction-by-pandas.ipynb # Jupyter Notebook with full code and analysis
README.md                            # Project documentation
```
## 📊 Dataset Overview
- Brand
- Processor
- RAM size and type
- Storage (HDD/SSD)
- GPU
- Display size and type
- Operating System
- Price (Target Variable)

## 🔍 Project Goals
- Clean and preprocess real-world laptop price data
- Analyze correlations between features and price
- Handle categorical variables
- Visualize key relationships
- Explore basic predictive modeling ideas

## Techniques Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn (for visualization)
  
## 📈 Key Insights
The project summarizes findings in the `LAPTOP_PRICE_PREDICTION_SUMMARY.txt` file, offering insights into:
- Key features affecting laptop prices
- Data distribution and outlier detection
- Steps taken for data cleaning and feature engineering

##  How to Run
1. Clone the repository:
 ```bash
   git clone https://github.com/zaralrubaie/laptop-prices-prediction-.git
```

## Laptop Price Prediction Model
- Model Used: RandomForestRegressor
- Cross-Validation R2 Scores: [0.7342, 0.7951, 0.8191, 0.7205, 0.8104]
- Mean CV R2 Score: 0.776
- Test Set R2 Score: 0.814

## Project Description:
This project predicts laptop prices based on various features such as
company, product type, CPU details, RAM, screen resolution, storage,
and GPU information. The data preprocessing pipeline includes feature
engineering, handling skewness, and encoding categorical variables.
The model is trained and evaluated using cross-validation to ensure
robustness.

- Author: Zahraa Alrubaie
- Date: 04/06/2025

Thank you for reviewing the project!
