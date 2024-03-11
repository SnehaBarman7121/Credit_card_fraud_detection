# Credit_card_fraud_detection

This code is a Python implementation for credit card fraud detection using two outlier detection models: Isolation Forest and Local Outlier Factor. 
Dataset Link:- https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Here's a summary of the code:

1. Import Libraries: The necessary libraries for data analysis, visualization, and machine learning are imported, including NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn modules.

2. Load and Sample Data: The credit card dataset is loaded from a CSV file. To reduce computation time, the dataset is then sampled to include only 10% of the data.

3. Explore Dataset: Basic exploratory analysis is performed, displaying information about the columns, shape, and description of the dataset. Histograms of each parameter are plotted to visualize the distribution of data.

4. Fraud Cases Analysis: The proportion of fraud cases in the dataset is calculated, and relevant information such as the number of fraud cases and valid transactions is printed.

5. Visualize Correlation Matrix: A heatmap is created to visualize the correlation matrix of the dataset, providing insights into potential relationships between features.

6. Define Features and Target Variable: The dataset is split into features (X) and the target variable (y), where the target is the "Class" column indicating fraud or valid transactions.

7. Outlier Detection Models: Two outlier detection models, Isolation Forest and Local Outlier Factor, are implemented with specific parameters. The code adjusts the outlier fraction if there are no fraud cases to avoid division by zero.

8. Evaluate Models: Both models are evaluated by fitting them to the features and comparing their predictions to the actual target values. The evaluation includes calculating the number of errors, accuracy scores, and generating a classification report.

This code provides a comprehensive approach to credit card fraud detection using outlier detection techniques and assesses the performance of the models using standard classification metrics.
