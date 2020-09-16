# classification adult dataset

The repository contains an attempt to build a prediction whether income exceeded $50k\year based on census data.
<ul>
  <li>Task: binary classification;</li>
  <li>Algorithmts to use: RandomForestClassifier, LogisticRegression, CatBoostClassifier, GaussianNB</li>
  <li>Measures: ROC AUC score, Accuracy</li>
</ul>

The data were scaled by Standard Scaler. The categorical features were encoded with Ordinal, OneHot encoders.\
The best model parameters were tuned by GridSearchCV.

<ul>
    <li>RandomForest accuracy score: 85.66%</li>
    <li>LogisticRegression accuracy score: 84.36%</li>
    <li>GaussianNB accuracy score: 82.4%</li>
    <li>CatBoostClassifier accuracy score: 86%</li>
    <li>DecisionTreeClassifier</li>
</ul>
