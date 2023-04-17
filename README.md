# Welcome to Company Bankruptcy Prediction Analysis
## _About_
This is a MINI-PROJECT for SC1015 (Intro to DSAI), which focuses on financial statements from Kaggle: [Company Bankruptcy Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction). For detailed walkthrough, please view the source code in order from:

1. [Data Extraction](https://github.com/VoidWitch/SC1015_miniproject_team8/blob/main/Data_Extraction.ipynb)
2. [Data Exploration And Visualization](https://github.com/VoidWitch/SC1015_miniproject_team8/blob/main/Data_Exploration_Visualization.ipynb)
3. [Random Forest Classifier](https://github.com/VoidWitch/SC1015_miniproject_team8/blob/main/Machine%20Learning%20Models%20with%20Evaluation.ipynb)
4. [XGB](https://github.com/VoidWitch/SC1015_miniproject_team8/blob/main/Machine%20Learning%20Models%20with%20Evaluation.ipynb)
5. [Logistic Regression](https://github.com/VoidWitch/SC1015_miniproject_team8/blob/main/Machine%20Learning%20Models%20with%20Evaluation.ipynb)

## _Contributors_
- @VoidWitch - Data Extraction, Exploration, Visualization
- @chesterchua - XGBoost Classifier, Logistic Regression, Model Evaluation
- @rebeladele - Random Forest Classifier, Video-making

## _Problem Definition_
- Are we able to predict the bankruptcy likelihood of a company based on its key financial statements?
- What model would be the best to predict it?

## _Models Used_
1. XGBoost Classifier
2. Random Forest Classifier
3. Logistic Regression
 

## _Conclusion_
Looking at our problem definition from another perspective: "Out of all bankrupt companies, how many did the model predict as bankrupt correctly?", we realized that it is alright for there to be false positives(not bankrupt but classified as bankrupt) as there is no harm in companies taking actions to boost their financial health or mitigate potential bankruptcy implications.
As such, we have determined that random forest classifier would be the best for our scenario since it is the overall highest recall score and we can predict the likelihood of a company's bankruptcy with an acceptable level of reliability and accuracy.

## _Project Insights_
- Based on our objectives and the metrics we want to use to evaluate our objectives, hyperparameter tuning may not be suitable.
- Accuracy score is not a suitable metric if the dataset is heavily imbalanced.
- In contrast to our initial expectations of XGBoost being the best ML model for prediction, it was outperformed by the other models when comparing recall score.
- In terms of performance, XGBoost and Random Forest are generally considered to be more powerful and accurate than Logistic Regression, particularly when dealing with large and complex datasets. However, if the dataset is relatively small, Logistic Regression may be a better choice.

## _References_
1. https://www.simplilearn.com/what-is-xgboost-algorithm-in-machine-learning-article#:~:text=XGBoost%20is%20a%20powerful%20open,decision%20trees%20and%20gradient%20boosting.
2. https://learn.g2.com/logistic-regression#:~:text=Logistic%20regression%20is%20a%20statistical,for%20solving%20binary%20classification%20problems.
3. https://www.ibm.com/topics/random-forest
4. https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction

