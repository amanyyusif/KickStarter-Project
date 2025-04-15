# KickStarter-Project

# Kickstarter Campaign Analysis & Prediction

This project explores the relationship between the number of backers and the amount pledged in Kickstarter campaigns using Python. It includes data cleaning, visualization, correlation analysis, and a simple linear regression model.

## 📊 Dataset
The dataset used is a Kickstarter dataset originally exported from Power BI. It includes:
- Project metadata (name, category, location, etc.)
- Campaign statistics (goal, pledged, backers, updates, comments, duration, success ratio %)

## 🔍 Objective
To determine the strength of the relationship between the number of backers and the total amount pledged, and to build a simple regression model that predicts the pledged amount.

## 🧠 Key Steps
- Load and clean the dataset (`pandas`)
- Visualize correlation (`seaborn`, `matplotlib`)
- Fit a linear regression model (`scikit-learn`)
- Evaluate the model using MSE, RMSE, MAE, and R²
- Derive the predictive equation

## 📈 Model Summary
**Equation:**

pledged = 68.45 × backers + 227.37

markdown
Copy
Edit

**Performance Metrics:**
- R² Score: `0.688`
- RMSE: `$31,694`
- MAE: `$2,471`

## 📁 Files
- `kickstarter_analysis.py`: Python code for data processing and modeling
- `DAI_kickstarterscrape_dataset.csv`: Cleaned dataset used
- `README.md`: Project documentation

## 🚀 How to Run
1. Clone the repo
2. Install requirements: `pip install -r requirements.txt`
3. Run the notebook or script
4. View regression plot and metrics

## 🛠️ Requirements
```bash
pandas
numpy
scikit-learn
matplotlib
seaborn
🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
