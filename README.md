# Classifying Startups - A Predictive Model for Determining Success
This project focuses on developing predictive models that classify startups based on key performance indicators, enabling investors and stakeholders to make data-driven decisions.

The primary goal of this project was to predict the success of startups by measuring their likelihood of continued operation using publicly available Crunchbase data sourced from Kaggle. Various machine learning models, including logistic regression, decision trees, random forests, and gradient boosting, were employed for the classification task. The analysis involved identifying key features influencing startup success in different scenarios and evaluating model performance based on metrics such as accuracy, precision, and recall. The findings provide insights into the factors driving startup success and highlight the comparative effectiveness of different classification models.

Steps implemented:

--> Data Cleaning

--> EDA

--> Logistic Regression

--> Decision Tree

--> Random Forest

--> Gradient Boosting

--> XG Boosting

#### Conclusion:

Each model was evaluated using several metrics, including accuracy, True Positive Rate (TPR), False Positive Rate (FPR), precision, F1 score, and ROC-AUC. We identified FPR as the most crucial evaluation metric, as it is important to avoid mistakenly classifying a failed startup as a successful one. A high FPR could lead to incorrect decisions, such as allocating resources to startups that are likely to fail. Therefore, models that minimize FPR while maintaining a good balance of precision and recall should be prioritized.

Among the models evaluated, the XGBoost classifier with the top 10 features stands out for its significantly lower FPR of 21%. While its accuracy is 73%, its precision (94%) and F1 score (84%) are well balanced, making it a strong performer in minimizing false positives. The Random Forest (Hybrid method), which also used the top 10 features, demonstrates the best trade-off by significantly reducing FPR to 58%, while maintaining a high F1 score (90%) and a higher accuracy of 83%. This makes it another top performer in terms of overall effectiveness.




