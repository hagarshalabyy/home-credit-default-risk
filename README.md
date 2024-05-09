This project involved an extensive exploratory data analysis (EDA) to derive valuable business insights and deepen my understanding of the dataset. 
Based on the findings from the EDA, I engineered new features that enhanced the data's utility for predictive modeling.

Given the dataset's complexity and the high number of features, it was essential to implement feature selection strategies. 
I employed a logistic regression model as an initial filter to evaluate the contribution of each feature. 
Features that did not enhance the model's performance were excluded.

For the modeling phase, I experimented with various algorithms to identify the model that delivers optimal performance. 
The best results were achieved using the XGBoost algorithm, which produced an AUROC score of 0.74343 on Kaggle test data.
