### Summary

This project focuses on detecting fraudulent transactions using a dataset from Kaggle, available at [Fraud Detection Dataset](https://www.kaggle.com/datasets/pranavrawat1301/fraud-detection). The dataset includes various features related to transactions, such as amounts, balances, and transfer percentages.

#### Key Steps:
1. **Data Exploration and Cleaning:**
   - Loaded the dataset and performed initial checks for missing or duplicate values.
   - Created new features such as `%transferred` and `%Received` to better understand transaction patterns.
   - Cleaned data by removing non-numeric values, handling NaNs, and filtering out irrelevant rows.

2. **Feature Engineering:**
   - Replaced categorical values with meaningful labels and removed unnecessary columns.
   - Generated features like `Frequency` to capture repeated transactions and computed the percentage metrics to provide insights into transaction behaviors.

3. **Exploratory Data Analysis (EDA):**
   - Visualized various aspects of the data, including distribution of frauds by type, amount, and frequency.
   - Used box plots, scatter plots, violin plots, and histograms to examine the relationships between features and fraud occurrence.
   - Analyzed the percentage of amounts transferred and received to identify patterns related to fraudulent activities.

4. **Feature Importance:**
   - Applied the `ExtraTreesClassifier` to determine feature importance and plotted the results to highlight the most influential features in predicting fraud.

5. **Predictive Modeling:**
   - Built and trained an Artificial Neural Network (ANN) for fraud prediction.
   - Achieved a high accuracy score of 98% on the test set, demonstrating the effectiveness of the model in identifying fraudulent transactions.

This project showcases a comprehensive approach to fraud detection, utilizing data cleaning, feature engineering, and advanced modeling techniques to achieve accurate results.

Feel free to explore the dataset and code to gain insights into fraud detection and model development.
