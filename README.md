# credit-card-fraud-detection
<br>
Author - ADITYA LAL
<BR>
Fraud Detection in Credit Card Transactions

Objective:
The goal of this project is to develop a machine learning model to detect fraudulent credit card transactions. Credit card fraud is a significant concern, and this model aims to identify unusual patterns in transactions that could indicate fraudulent activity.

Dataset:

The dataset used for this project contains information about credit card transactions, including features such as time, transaction amount, and various V1 to V28 features obtained through a PCA transformation for privacy reasons.
It is a highly imbalanced dataset with a large number of legitimate transactions (Class 0) and a small number of fraudulent transactions (Class 1).
Data Exploration:

The dataset is loaded and examined to understand its structure and features.
There are no missing values in any column, making it suitable for analysis.
Data Distribution:

The distribution of transactions shows a severe imbalance with a vast majority being legitimate (Class 0) and a very small number being fraudulent (Class 1).
Statistical Analysis:

Statistical measures such as mean, standard deviation, and quartiles are computed for both legitimate and fraudulent transactions.
These measures provide insights into the differences in transaction amounts between the two classes.
Under-Sampling:

To address the imbalance, a balanced dataset is created by under-sampling legitimate transactions to match the number of fraudulent transactions.
Modeling:

Logistic Regression is chosen as the classification algorithm for its simplicity and effectiveness in binary classification tasks.
The dataset is split into features (X) and the target variable (Y), and further divided into training and testing sets.
Model Training:

The Logistic Regression model is trained using the training data.
Model Evaluation:

The accuracy of the model is evaluated on both the training and testing datasets.
The model demonstrates high accuracy on both datasets, indicating its ability to generalize well.
Results:

The project successfully builds a fraud detection model that can identify potentially fraudulent credit card transactions.
The model achieves high accuracy on both training and testing datasets.
Conclusion:

The developed model can be deployed in a real-world scenario to enhance credit card transaction security by automatically detecting and preventing fraudulent transactions.
Future Work:

Further improvements can be made by exploring other machine learning algorithms, fine-tuning parameters, and incorporating more advanced techniques such as anomaly detection.
This structured explanation should provide a comprehensive overview of the project, suitable for a 15-minute interview presentation. Feel free to customize it based on your specific experiences and details of the project.





