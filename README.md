RAINFALL PREDICTION 

This project predicts **whether it will rain tomorrow** using historical weather data
It involves data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning model training**  


1. **Data Understanding & Cleaning**
   - Handle missing values (no missing values)
   - Remove/transform outliers  
   - Convert categorical features (e.g., Wind Direction)  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of rainfall values  
   - Correlation between all numeric columns. 
   - Class balance check for `RainTomorrow`
  
3. **Distribution Analysis**
   - Histogram plot for all numeric columns and analyse the distribution
   - Transform the column which has most skew value with transformation types(log transformation,sqareroot transformation)

4. **Feature Engineering**
   - Encode wind direction into angles (0–360°) with sin/cos transformation  
   - Create new features:
   - `WindRange = WindGustSpeed - WindSpeed9am`  
   - Difference between morning & afternoon wind directions
   - Average of morning & afternoon (for finding whether the humidity,pressure,temperature increase or decrease)
   labeling/Mapping
    - RainToday -> Yes(1),No(0)
    - RainTomorrow -> Yes(1),No(0)
   - Scale numerical features  

5. **Prediction**
   - Final output: `RainTomorrow` → Yes / No

     
Tech Stack
Python: Programming language for data manipulation and analysis.
Pandas: Data manipulation and analysis.
Matplotlib: Plotting and visualization.
Seaborn: Statistical data visualization.
Numpy: Numerical computing

