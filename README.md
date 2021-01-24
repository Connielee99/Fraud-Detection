# Fraud-Detection
- Highly imbalanced data
- Time related raw data and aggregates are important/predictive of fraud

#### Simple RandomForest:
- accuracy_score is: : 0.9948692007515537
- roc_auc_score is: : 0.7576728137888975
- f1_score is: : 0.6712962962962962
- recall = 0.5052264808362369
- precision = 1.0

#### Simple RandomForest with Smote Sampling:
- accuracy_score_sm is: : 0.9948330683624801
- roc_auc_score_sm is: : 0.7641708827127756
- f1_score_sm is: : 0.6697459584295612
- recall or sens_sm = 0.5052264808362369
- precision_sm = 0.9931506849315068

#### Simple XGBoost with Smote Sampling:
- accuracy_score_sm is: : 0.9947969359734066
- roc_auc_score_sm is: : 0.7766622272503662
- f1_score_sm is: : 0.6682027649769584
- recall or sens_sm = 0.5052264808362369
- precision_sm = 0.9863945578231292
