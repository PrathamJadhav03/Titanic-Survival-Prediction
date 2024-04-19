# Titanic Survival Prediction using Logistic Regression
# Overview
The sinking of the RMS Titanic in 1912 is one of the most famous maritime disasters in history. In this project, I developed a machine learning model to predict the survival of passengers on the Titanic based on various passenger characteristics.

The dataset used in this project is the Titanic - Machine Learning from Disaster dataset from Kaggle, which contains information about the passengers, including their age, sex, class, and whether they survived the sinking.

# Project Objectives
The main objectives of this project were:

Load and preprocess the Titanic dataset, handling missing values and encoding categorical features.
Split the dataset into training and testing sets.
Train a Logistic Regression model on the training data.
Evaluate the model's performance using accuracy and classification report.
Visualize the distribution of survived and non-survived passengers.

# Implementation
The project is implemented in Python using the following libraries:

* `pandas`: for data manipulation and analysis
* `sklearn`: for machine learning algorithms and evaluation metrics
* `matplotlib` and `seaborn`: for data visualization
The code is organized in a Jupyter Notebook and can be found in the titanic-survival-prediction.ipynb file.

Results
After loading and preprocessing the Titanic dataset, I split it into training and testing sets. I then trained a Logistic Regression model on the training data and evaluated its performance on the test set.

The model achieved an accuracy of 80.45% on the test set, which is a reasonably good performance. The classification report provides more detailed insights, showing that the model has a higher precision and recall for the "not survived" class compared to the "survived" class.

To visualize the distribution of survived and non-survived passengers, I created a bar chart using `seaborn`. This plot clearly shows the imbalance in the dataset, with more non-survived passengers than survived passengers.

Conclusion
This project demonstrates the use of Logistic Regression, a popular machine learning algorithm, to predict the survival of passengers on the Titanic. While the model achieved a decent accuracy, the results indicate that there is room for improvement, perhaps by exploring other machine learning techniques or incorporating additional feature engineering.

The code and detailed explanations are available in the Jupyter Notebook. Feel free to explore the project and provide feedback or suggestions for improvement.