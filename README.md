Bank Customer Churn Prediction
1. Dataset Collection

The bank customer churn dataset is collected and loaded into Python using the Pandas library. It contains customer information such as credit score, country, gender, age, tenure, balance, number of products, credit card status, active membership, estimated salary, and churn status.

2. Data Exploration

The dataset is explored to understand its structure, data types, and summary statistics. Missing values are checked to ensure the dataset is clean before model building.

3. Data Preprocessing

The dataset is prepared for machine learning by converting categorical features such as country and gender into numerical values using Label Encoding. The target variable is churn, while the remaining columns are used as input features.

4. Data Splitting

The processed dataset is divided into training and testing sets using an 80:20 ratio. This allows the model to learn from one portion of the data and evaluate its performance on unseen data.

5. Feature Scaling

The numerical features are standardized using StandardScaler to improve the model's performance and ensure all features are on the same scale.

6. Model Training

A Random Forest Classifier is trained using the training dataset to learn patterns and relationships between customer attributes and churn status.

7. Prediction

The trained model predicts whether customers in the test dataset are likely to churn or remain with the bank.

8. Model Evaluation

The model's performance is evaluated using the Accuracy Score, which measures how accurately the model predicts customer churn.

9. Data Visualization

A churn distribution chart is created using Seaborn and Matplotlib to visualize the number of customers who churned and those who remained.

