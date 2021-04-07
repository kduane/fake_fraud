# Fraud Detection on Simulated Financial Transactions
## Purpose:

The purpose of this study is to identify fraudulent transactions in an extremely unbalanced dataset.  

### Data Dictionary:

|                | type    | description                                          |
|:--------------:|---------|------------------------------------------------------|
| step           | int     | 1 hour unit of time                                  |
| type           | obj     | kind of transaction (ie payment, transfer, cash_out) |
| amount         | float64 | dollar amount of transaction                         |
| nameOrig       | obj     | identifier of origin account                         |
| oldBalanceOrig | float64 | pre-transaction balance of origin account            |
| newBalanceOrig | float64 | post-transaction balance of origin account           |
| nameDest       | obj     | identifier of destination account                    |
| oldBalanceDest | float64 | pre-transaction balance of destination account       |
| newBalanceDest | float64 | post-transaction balance of destination account      |
| isFraud        | int64   | boolean, 1 for Fraud, 0 for not                      |
| isFlaggedFraud | int64   | boolean, 1 for Fraud, 0 for not                      |

### Phase 1 - Problem Definition  
    1.1 Broad Goals  
    1.2 Data Source  
    1.3 Problem Statement   

### Phase 2 - Data Gathering  
    2.1 Load Files   

### Phase 3 - Exploratory Data Analysis  
    3.1 Dataset Shape   
    3.2 Fraud by Transaction Type   
    3.3 Examining Confirmed Fraud Samples   
    3.4 Exploring Engineered Features   
    3.5 Correllation to Fraud   
 
### Phase 4 - Modeling  
    4.1 Load/ Clean
    4.2 Feature Engineering
    4.3 Train/Test/Split  
    4.4 Methods for Handling Imbalanced Classes   
        - oversampling   
        - undersampling  
        - SMOTE 
    4.5 Logistic Regression    
    4.6 Random Forest Classifier   
    4.7 XGB Classifier   

### Phase 5 - Model Analysis  
    5.0 Baseline Score  
    5.1 Compare Accuracy Scores  
    5.2 Model Selection

### Phase 6 - Conclusions  
    6.1 Revisit 1.3 Problem Statement  
    6.2 Conclusions  
    6.3 Recommendations for Further Research 

###  Acknowledgements

PaySim first paper of the simulator:

E. A. Lopez-Rojas , A. Elmir, and S. Axelsson. "PaySim: A financial mobile money simulator for fraud detection". In: The 28th European Modeling and Simulation Symposium-EMSS, Larnaca, Cyprus. 2016