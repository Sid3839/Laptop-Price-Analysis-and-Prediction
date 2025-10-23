# Laptop-Price-Analysis-and-Prediction
Machine Learning project that analyzes and predicts laptop prices using Python. Includes data preprocessing, exploratory data analysis (EDA), and model comparison (Linear Regression, Random Forest, and XGBoost).


#📂 Project Overview
The project includes:
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Model training and evaluation using Linear Regression, Random Forest, and XGBoost
  
#🧰 Technologies Used
- Python 3
- Google Colab / Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost

#📊 Dataset
The dataset (`laptop_prices.csv`) contains specifications and prices of **1,275 laptops** from multiple brands.  
Key columns include:

| Feature | Description |
|----------|-------------|
| Company | Laptop brand (e.g., Apple, HP, Dell, Lenovo) |
| TypeName | Category (Ultrabook, Gaming, Notebook, etc.) |
| Inches | Screen size |
| RAM | Memory (GB) |
| OS | Operating System |
| Weight | Weight of the laptop |
| CPU_company / GPU_company | Processor and graphics brand |
| PrimaryStorage / SecondaryStorage | Storage capacity |
| Price_euros | Target variable (price in euros) |

#🧮 Steps Followed

1. Import Libraries  
   Load all required dependencies.

2. Load Dataset  
   Imported the dataset from Colab and verified data types and structure.

3. EDA (Exploratory Data Analysis) 
   - Distribution plots for prices  
   - Company and OS frequency  
   - Relationships between features and price

4. Data Preprocessing  
   - Removed null values  
   - Encoded categorical variables  
   - Split dataset into training (80%) and testing (20%)

5. Model Training  
   Trained three regression models:
   - Linear Regression  
   - Random Forest Regressor  
   - XGBoost Regressor  

6. Model Evaluation  
   Compared models using:
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R² Score

#🏁 Results

| Model | RMSE | R² Score |
|--------|------|----------|
| Linear Regression | 1983.74 | -6.92 |
| Random Forest | (varies) | (varies) |
| XGBoost | (varies) | (varies) |

> 🔍 Random Forest and XGBoost outperformed Linear Regression due to their ability to handle non-linear feature interactions.

