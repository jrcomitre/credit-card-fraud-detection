### Credit Card Fraud Detection with Machine Learning <br>
This project explores credit card transactions data to develop fraud detection models using data science and machine learning techniques.

📁 About the Dataset
The dataset contains credit card transactions made by European cardholders in September 2013. Transactions occurred over two days, totaling 284,807 transactions, with 492 labeled as fraud.

🔍 Key characteristics:

The dataset is highly imbalanced, with frauds making up only 0.172% of all transactions.

It includes only numerical features, most of which were transformed using PCA (Principal Component Analysis).

The only features not transformed are:

Time: Seconds elapsed between each transaction and the first transaction in the dataset.

Amount: Transaction amount.

The target variable is Class:

0 → Legitimate transaction

1 → Fraudulent transaction

📉 Due to the class imbalance, the recommended evaluation metric is the Area Under the Precision-Recall Curve (AUPRC). Traditional accuracy is misleading in this context.

🎯 Project Goals
Perform exploratory data analysis (EDA)

Handle class imbalance using techniques like undersampling, oversampling (SMOTE, etc.)

Train supervised models (Logistic Regression, Random Forest, XGBoost, etc.)

Evaluate models based on recall, precision, and AUPRC

Explore anomaly detection and unsupervised learning methods

🛠 Technologies Used
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook
