# Predicting_Online_Purchasing_Intension
Real-time shopper behaviour analysis system that calculates the likelihood of whether a shopper will make a purchase during a given session. 

This project focuses on building a machine learning model to predict whether an online shopper will complete a purchase during a browsing session. Using the Online Shoppers Purchasing Intention Dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset), this work explores binary classification in an imbalanced dataset context to support real-world e-commerce analytics.

## Objectives 
- Predict purchase intentions of online shoppers.
- Identify behavioural patterns that distinguish purchasing users from non-purchasing ones.
- Improve e-commerce conversion rates through predictive insights.

## Notable Methods

### Data Preprocessing

- Addressed heavy class imbalance using SMOTE (Synthetic Minority Oversampling Technique) combined with undersampling.

### Feature Selection

- Employed Minimum Redundancy Maximum Relevance (mRMR) algorithm to select the most informative and least redundant features.
- Compared with tree-based feature importance (Random Forests) to validate relevance.

## Model Development 
- Hyperparameter tuning was performed using Grid Search with cross-validation, optimizing for F1 score to ensure balanced precision and recall.

## Evaluation 
- Analyzed model performance visually through Confusion Matrices for top-performing classifiers (Bagged Trees and Boosted Trees).
- Boosted Trees achieved the best overall performance, showing strong true positive rates and robust generalization.

## References
- Sakar, C. O., Polat, S., Katırcıoğlu, M. A., & Kastro, Y. (2018). Real-time prediction of online shoppers’ purchasing intention using multilayer perceptron and LSTM recurrent neural networks. Neural Computing & Applications, 31(10), 6893–6908.
- Ding, A. W., Li, S., & Chatterjee, P. (2015). Learning user real-time intent for optimal dynamic web page transformation. Information Systems Research, 26(2), 339–359.
- Dataset : https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset
