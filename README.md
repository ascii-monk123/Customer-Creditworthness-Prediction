# Customer-Creditworthness-Prediction
Customer Creditworthness Prediction using Machine Learning

# Motivation
<ul>
<li>Meet Alex, a bank representative trying to see if his customers are likely to return the loans they have been approved of. </li>

<li>Credit risk evaluation plays a crucial role for financial institutions, as lending decisions can lead to real and immediate losses. </li>

<li>One of the most challenging tasks in credit risk management is predicting defaults – identifying borrowers who are likely to fail in repaying their loans.</li>

<li>Banks face critical decisions about granting loans to borrowers, necessitating accurate credit risk assessment.</li>
</ul>

# Methdology
<ol>
<li> <b>Data Loading and Exploration:</b> Load training and testing datasets. Conduct basic exploratory data analysis (EDA) to check for missing values, data types, and unique values.
  </li>
<li> <b>Data Preprocessing:</b>
Handle categorical variables using label encoding and one-hot encoding. Performing data normalization.
</li>
<li> <b>Model Building and Evaluation:</b>
  <ul><li><b>LightGBM:</b> A gradient boosting model trained on the entire dataset, with feature importance analysis.</li>
<li><b>Logistic Regression and SVM:</b> Trained on a subset of features selected based on LightGBM’s feature importance.</li>
<li>Other models like Random Forest, XGBoost, CatBoost, and AdaBoost are used for feature selection. Step 2 was repeated for all.</li>
<li>Evaluate model performance using accuracy and classification reports.</li>
  </ul>
     </li> 
</ol>
