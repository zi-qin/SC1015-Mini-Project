# SC1015 Mini-Project

# Predicting Employee Churn

## About

- This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on the career experience of employees in the United States from 2003 to 2004. For detailed walkthrough, please view the source code in order from:
1. [Data Preparation](https://github.com/zi-qin/SC1015-Mini-Project/blob/main/Data%20Preparation.ipynb)
2. [Exploratory Data Analysis](https://github.com/zi-qin/SC1015-Mini-Project/blob/main/Exploratory%20Data%20Analysis.ipynb)
3. [Machine Learning](https://github.com/zi-qin/SC1015-Mini-Project/blob/main/Machine%20Learning.ipynb)
4. [Data Visualisation](https://github.com/zi-qin/SC1015-Mini-Project/blob/main/Data%20Visualisation.ipynb)

## Dataset 
Professional Worker Career Experience Survey, United States, 2003-2004 : https://www.icpsr.umich.edu/web/ICPSR/studies/26782/datadocumentation

## Problems 
- Which variables best predict employee’s intention to leave their jobs?
- Which classifier best predicts employee’s intention to leave their jobs?


## Models Used
- Random Forest
- Logistic Regression



## Conclusion

- The Random Forest Tree classifer has a higher accuracy in predicting the employee’s intention to leave their jobs than Logistic Regression classifier. 
- From the results of Random Forest Tree classifier, it suggests that "Age" is a key predictor of employee's intention to leave his or her employer.-
- The variable "Stress" is also one of the key predictor as it is the second best model among the Top 3 Random Forest models and the best model among the Logistic Regression models. 

## What did we learn from this project?

- Apply and ApplyMap method for data preparation
- Stacked bar charts to visualise relationships between categorical variables
- SelectFromModel and RFE from scikit-learn Feature Selection module
- Logistic regression as a classifier
- Concepts on F1 score and AUC-ROC curve

## Contributions

- Data Preparation: Zi Qin
- Exploratory Data Analysis: Le Yi, Zhaoding
- Machine Learning & Data Visualisation: All members
- Presentation video: All members

# References

- <https://towardsdatascience.com/how-to-drop-rows-in-pandas-dataframes-with-nan-values-in-certain-columns-7613ad1a7f25>
- <https://towardsdatascience.com/introduction-to-pandas-apply-applymap-and-map-5d3e044e93ff>
- <https://www.analyticsvidhya.com/blog/2021/05/a-comprehensive-guide-to-data-analysis-using-pandas-hands-on-data-analysis-on-imdb-movies-data/>
- <https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html>
- <https://towardsdatascience.com/feature-selection-using-random-forest-26d7b747597f>
- <https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html>
- <https://www.saedsayad.com/categorical_categorical.html>
- <https://scikit-learn.org/stable/auto_examples/ensemble/plot_forest_importances.html>
- <https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.SelectFromModel.html>
- <https://towardsdatascience.com/feature-selection-using-random-forest-26d7b747597f>
- <https://www.geeksforgeeks.org/plotting-multiple-bar-charts-using-matplotlib-in-python/>
- <https://towardsdatascience.com/4-ways-to-visualize-individual-decision-trees-in-a-random-forest-7a9beda1d1b7>
- <https://www.datacamp.com/tutorial/random-forests-classifier-python>
- <https://www.statology.org/plot-roc-curve-python/>
- <https://towardsdatascience.com/a-look-into-feature-importance-in-logistic-regression-models-a4aa970f9b0f>
- <https://www.geeksforgeeks.org/adding-value-labels-on-a-matplotlib-bar-chart/>
- <https://towardsdatascience.com/powerful-feature-selection-with-recursive-feature-elimination-rfe-of-sklearn-23efb2cdb54e>
- <https://towardsdatascience.com/understanding-random-forest-58381e0602d2#:~:text=The%20random%20forest%20is%20a,that%20of%20any%20individual%20tree.>
- <https://www.sciencedirect.com/topics/computer-science/logistic-regression>
