# titanic-survival-prediction
Description

This Titanic Survival Prediction project uses machine learning techniques to analyze passenger data and predict whether a passenger survived the Titanic disaster. The goal of the project is to understand how different demographic and travel-related factors—such as age, gender, ticket class, and family size—affected the chances of survival. By preprocessing the dataset, selecting meaningful features, training a classification model, and visualizing key survival patterns, this project demonstrates the complete workflow of building a predictive model.

The titanic_survival_prediction.py script performs several essential tasks. It begins by loading the dataset and handling missing values, such as filling missing Age values with the median and replacing missing Embarked entries with the most common value. Categorical variables like Sex and Embarked are label-encoded into numerical format for model compatibility. The project uses key features such as Age, Fare, Pclass, Sex, SibSp, and Parch to build the model. After splitting the data into training and testing sets, a Logistic Regression classifier is trained to predict survival outcomes.

The model is evaluated using standard performance metrics such as accuracy, precision, recall, and F1-score to measure how well it generalizes to unseen data. In addition to model training and evaluation, the project includes visualizations that provide deeper insights into survival trends. These include survival rates across gender, passenger class, and different age groups, helping to clearly interpret the impact of various factors on survival.

This project is implemented entirely in Python using data science libraries such as Pandas for data manipulation, NumPy for numerical operations, Scikit-learn for preprocessing and model building, and Matplotlib for visualization. It serves as a beginner-friendly yet complete example of a supervised machine learning classification project.
