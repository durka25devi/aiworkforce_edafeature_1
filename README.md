RAINFALL PREDICTION 

This project predicts **whether it will rain tomorrow** using historical weather data
It involves data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning model training**  


Project Workflow  

1. **Data Understanding & Cleaning**
   - Handle missing values  
   - Remove/transform outliers  
   - Convert categorical features (e.g., Wind Direction)  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of rainfall values  
   - Correlation between temperature, humidity, pressure, and rain  
   - Class balance check for `RainTomorrow`  

3. **Feature Engineering**
   - Encode wind direction into angles (0–360°) with sin/cos transformation  
   - Create new features:
   - `WindRange = WindGustSpeed - WindSpeed9am`  
   - Difference between morning & afternoon wind directions  
   - Scale numerical features  

4. **Model Training**
   - Train ML models such as Logistic Regression, Random Forest, XGBoost  
   - Evaluate using accuracy, precision, recall, F1-score  

5. **Prediction**
   - Final output: `RainTomorrow` → Yes / No

     
Tech Stack
Python: Programming language for data manipulation and analysis.
Pandas: Data manipulation and analysis.
Matplotlib: Plotting and visualization.
Seaborn: Statistical data visualization.
Numpy: Numerical computing

