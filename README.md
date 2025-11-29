# Online-Payment-Fraud-Detection
This project aims to detect fraudulent online payment transactions using various Machine Learning algorithms.
With the rise of digital payments (UPI, wallets, net banking, etc.), fraud detection has become essential to ensure secure financial transactions.

This project uses a large dataset of payment transactions and applies different ML models to classify whether a transaction is fraud (1) or genuine (0).

***** DATASET DISCRIPTION ****
The dataset contains 6.3 million transactions, with the following key features:

Column	            Description
step	              Time unit of the transaction
type	              Transaction type (CASH_OUT, TRANSFER, etc.)
amount	            Transaction amount
nameOrig	          Sender account ID
oldbalanceOrg	      Sender balance before transaction
newbalanceOrg      	Sender balance after transaction
nameDest	          Receiver account ID
oldbalanceDest	    Receiver balance before transaction
newbalanceDest	    Receiver balance after transaction
isFraud	            Target variable (1 = Fraud, 0 = Legit)

***** Exploratory Data Analysis *****

Distribution of transaction types
Fraud vs Non-fraud count
Amount vs Type analysis
Correlation heatmap
Visualizing step-wise distribution

***** Machine Learning Models Used *****

Logistic Regression
Random Forest Classifier
XGBoost Classifier 

Code Link: https://colab.research.google.com/drive/1jW-R3WUs8jdRQBcNH6qUDOml94hY0b9U
Dataset is uploaded in the repository
