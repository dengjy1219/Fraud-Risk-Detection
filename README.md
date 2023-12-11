# Fraud Risk Detection of Auto Insurance Based on SMOTE and Ensemble Models
Undergraduate Capstone

Jun 2023

## Summary

With the development of China's economic level, the improvement of the automobile industry and the continuous increase in the number of motor vehicles, automobile insurance has become the largest type of property insurance. At the same time, criminals take advantage of auto insurance fraud to obtain huge amount of money, causing serious social harm. The comprehensive reform of auto insurance in 2020 put forward the goal of "reducing prices, increasing insurance, and improving quality". How to use intelligent risk assessment methods to strengthen the identification of auto insurance fraud risks is an important aspect of risk control for property insurance companies. This paper uses machine learning methods to analyze open source claims data, and proposes a model that can effectively identify the risk of auto insurance fraud to help auto insurance risk control.

First, through exploratory analysis of claims data, the impact of different data features on fraud risk is explored, and a visualization of important features is given. Furthermore, according to the missing characteristics and feature collinearity of the data, a strategy for handling missing values is given. At the same time, the derived features are constructed according to the meaning of the features, and the dimensionality reduction of the data is carried out by using the Wrapper selection method, so as to construct the feature engineering with the ability to distinguish auto insurance fraud. Finally, six machine learning models of support vector machine, decision tree, random forest, XGBoost, LightGBM and CatBoost are used for modeling, and the advantages and disadvantages of the ensemble model and the benchmark model are compared, and the Stacking method is used for model fusion. In addition, considering that data imbalance has a great impact on model performance, the ensemble model and SMOTE algorithm are combined to further improve the overall performance of the model.

The research results show that: the final optimal model is the fusion model of XGBoost and CatBoost optimized by the sampling algorithm, and the AUC score reaches 0.80433, so the model with strong identification ability of auto insurance fraud risk is obtained. Therefore, the machine learning model can effectively help the anti-fraud of auto insurance. But in practice, it should also improve the data dimension and quality of more claims data, develop new technologies such as knowledge graphs and small sample learning, and mine more value from data. Promoting multi-party data sharing under the premise of information security, information interoperability and intercommunication can be realized. This is of positive significance to the healthy development of China's auto insurance industry.

**Keywords: auto insurance; insurance fraud risk; unbalanced data; machine learning**

