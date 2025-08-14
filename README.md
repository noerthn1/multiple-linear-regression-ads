# Multiple-linear-regression-ads
This project applies Multiple Linear Regression to predict sales based on advertising budgets across TV, Radio, and Newspaper. The model estimates how each marketing channel contributes to sales, providing insights for budget allocation and marketing strategy.

# 📂 Dataset
The dataset (advertising.csv) contains:
• TV – Advertising budget spent on TV ads (in thousands of dollars)
• Radio – Advertising budget spent on radio ads (in thousands of dollars)
• Newspaper – Advertising budget spent on newspaper ads (in thousands of dollars)
• Sales – Product sales (in thousands of units)

# 🛠️ Technologies Used
• Python 3
• Pandas – Data manipulation
• NumPy – Numerical operations
• Matplotlib – Data visualization
• scikit-learn – Machine learning model

# 📈 Model Information
• Algorithm: Multiple Linear Regression
• Target Variable (y): Sales
• Features (X): TV, Radio, Newspaper
• Train/Test Split: 80% train, 20% test

# 🔍 Model Performance
• Intercept: 4.7732
• Coefficients:
• TV: 0.05
• Radio: 0.11
• Newspaper: -0.00
• R² Score: 0.8645
• Mean Squared Error: 4.5225
 This means the model explains 86.45% of the variance in sales data.

# 🚀 How to Run
1. Clone this repository :
   git clone https://github.com/your-username/multiple-linear-regression.git
2. Navigate to the project folder:
   cd multiple-linear-regression
3. Install required packages:
   pip install -r requirements.txt
4. Run on jupyter notebook or python script
