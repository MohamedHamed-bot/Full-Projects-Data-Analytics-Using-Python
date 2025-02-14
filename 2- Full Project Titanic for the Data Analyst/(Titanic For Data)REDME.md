#  Titanic Data Analysis project,
# 1- Project Overview
This project analyzes the Titanic dataset to understand factors affecting passenger survival. It involves data cleaning, exploration, and predictive modeling to uncover insights about survival rates based on passenger demographics and ticket class.
# 2- Process Details
1. Data Import & Cleaning:
   - Loaded dataset using pandas
   - Handled missing values (age, embarked, etc.)
   - Converted categorical data (e.g., sex, embarked) into numerical values
2. **Exploratory Data Analysis (EDA):**
   - Visualized survival rates based on gender, class, and age
   - Checked correlations using heatmaps
3. **Feature Engineering & Model Training:**
   - Selected relevant features (Pclass, Sex, Age, SibSp, Parch, Fare)
   - Applied Logistic Regression, Decision Trees, and Random Forest for prediction
   - Evaluated models using accuracy, precision, recall, and F1-score
# 3- Analysis
   - Survival rate was highest in 1st class and lowest in 3rd class.
   - Women had a much higher survival rate than men.
   - Children (age < 10) had better survival odds compared to adults.
   - Fare price positively correlated with survival (higher fares, higher survival).
# 4- Key Insights
  - Gender was the most significant factor (Women: 74% survival, Men: 18%).
  - Class played a crucial role (1st Class: 62% survival, 3rd Class: 25%).
  - Passengers traveling alone had lower survival chances than those with family.
  - Decision Tree & Random Forest performed best for predicting survival.
# 5- Visualization
  - Bar charts comparing survival rates by gender, class, and embarkation point.
  - Heatmaps to show correlations between variables.
  - Boxplots analyzing fare distribution among survivors vs. non-survivors.
  - Confusion matrix evaluating model predictions.






















