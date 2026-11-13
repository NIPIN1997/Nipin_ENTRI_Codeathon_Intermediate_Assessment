# Machine Learning
## Preprocessing
1. The dataset is loaded into a dataframe.
2. The dataset is checked for duplicate rows. No duplicate rows were identified in the dataset.
3. The dataset is checked for missing values. There were no missing values in the dataset.
4. The outliers were removed.
5. The skewness of the columns were corrected accordingly.
6. The categorical columns were encoded.
7. The dataset is scaled using StandardScaler.
## Model Training
The regression algorithms used are:
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boost Regressor
5. Support Vector Regressor

For each model the following parameters are calculated:
1. Mean Absolute Error(MAE)
2. Mean Squared Error(MSE)
3. R2 Score
## Model Comparison
Random Forest Regressor was identified as the best model based on MAE, MSE and R2 score.
## Feature Selection
The 10 most important features of the dataset were identified using Random Forest.
## Hyper Parameter Tuning
The dataset was modified to include only the most important features. The Random Forest Regressor model was hyper tuned using GridSearchCV.
## Conclusion
1. The dataset didnot have any missing or duplicate values.
2. The outliers were removed.
3. The skewness of the all the columns except the target column was corrected.
4. The data was scaled using StandardScaler.
5. Multiple models were trained on the dataset and the performance metrics were calculated. Based on the performance metrics Random Forest Regressor was identified as the best model.
6. The best features of the dataset were identified using Random Forest.
7. After using only these features the Random Forest Regressor model was hyper tuned using GridSearchCV.
8. The R2 Score after feature selection and hyper parameter tuning is remaining the same as before because Random Forest is already a well performing and optimized algorithm and also we can conclude that the selected top 10 features are the only features that matter.