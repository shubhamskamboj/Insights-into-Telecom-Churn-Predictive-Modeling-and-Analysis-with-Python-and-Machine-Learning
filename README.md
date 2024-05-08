🔍📊 In this repository, we've embarked on an end-to-end journey of Exploratory Data Analysis (EDA), meticulously unraveling the intricacies of customer behavior. Through astute analysis, we've identified key characteristics hinting at potential churn. Leveraging these insights judiciously, we've artfully crafted a predictive model poised to anticipate customer churn. 🛠️💡
# Insights into Telecom Churn: Predictive Modeling and Analysis with Python and Machine Learning 📊📈

## Data Exploration and Analysis

1. **Insights from Data Analysis**
   - A significant portion (approximately 75%) of customers have a tenure of less than 55 months.
   - The average monthly charges stand at USD 64.76, with 25% of customers paying more than USD 89.85 per month.

2. **Data Imbalance**
   - Ratio: 73:27 (highly imbalanced) 📉
   - Analysis Approach: Considering other features separately with target values to gain insights.

3. **Missing Data - Initial Intuition**
   - No missing data found. 🚫🔍

## Data Cleaning

4. **Missing Value Treatment**
   - 11 missing values in the 'TotalCharges' column, negligible compared to the total dataset. 📉

5. **Handling Categorical Variables**
   - Converted categorical variables into dummy variables using one-hot encoding. 🔢

6. **Drop Columns**
   - Dropped 'customerID' and 'tenure' columns not required for processing. 🗑️

## Data Exploration Continued

7. **Bivariate Analysis**
   - Explored correlations between predictors and 'Churn'. 📈

8. **Churn Analysis**
   - Discovered insights into customer churn based on various factors. 🔄

## Model Building

9. **Decision Tree Classifier**
   - Initial accuracy was low due to dataset imbalance.
   - Applied SMOTEENN (UpSampling + ENN) to improve results. 🌳🔍

10. **Random Forest Classifier**
    - Without oversampling: Achieved moderate results.
    - After SMOTEENN: Improved accuracy, precision, recall, and f1-score. 🌲📈

## Conclusion

Based on our analysis and modeling efforts, we've gained valuable insights into telecom churn patterns and developed predictive models to anticipate customer churn. Moving forward, we can explore additional classifiers to further enhance model performance and refine our strategies for customer retention. 🎯💼

