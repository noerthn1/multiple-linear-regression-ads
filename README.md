# Multiple-linear-regression-ads
This project applies Multiple Linear Regression to predict sales based on advertising budgets across TV, Radio, and Newspaper. The model estimates how each marketing channel contributes to sales, providing insights for budget allocation and marketing strategy.

# 📂 Dataset
The dataset (advertising.csv) contains:
1. TV – Advertising budget spent on TV ads (in thousands of dollars)
2. Radio – Advertising budget spent on radio ads (in thousands of dollars)
3. Newspaper – Advertising budget spent on newspaper ads (in thousands of dollars)
4. Sales – Product sales (in thousands of units)

# 🛠️ Technologies Used
1. Python 3
2. Pandas – Data manipulation
3. NumPy – Numerical operations
4. Matplotlib – Data visualization
5. scikit-learn – Machine learning model

# 📈 Model Information
1. Algorithm: Multiple Linear Regression
2. Target Variable (y): Sales
3. Features (X): TV, Radio, Newspaper
4. Train/Test Split: 80% train, 20% test

# 🔍 Model Performance
1. Intercept: 4.7732
2. Coefficients:
- TV: 0.05
- Radio: 0.11
- Newspaper: -0.00
3. R² Score: 0.8645
4. Mean Squared Error: 4.5225
 This means the model explains 86.45% of the variance in sales data.

# 🚀 How to Run
1. Clone this repository :
- git clone https://github.com/your-username/multiple-linear-regression.git
2. Navigate to the project folder:
- cd multiple-linear-regression
3. Install required packages:
- pip install -r requirements.txt
4. Run on jupyter notebook or python script
