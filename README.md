# credict_card_fraud_detection

###### Model : `Catboost`
###### Library : `Catboost`, `Imblearn`, `Scikit-Learn`
###### Keywords : `Machine Learning`, `Unbalanced Data`, `SMOTE`, `NearMiss`

# Description
This is an extremely unbalanced data set, with only 1.34% of abnormal transactions. \
I built two models after feature engineering, the naive one has strong generalization, \
and another one was processed by SMOTE + ENN, which has a very high recall that means it can detect most of the fraudulent transcations.

-----------------------------------------------------

### Model1 : Naive Modeling (catboost)

Precision of model：0.7470067673086934

Recall of model：0.7237726967047747

F1_score of model：0.7352062163777645

F1_score of model in test set : 0.7945589782

---

Feature Importance: \
![image](https://github.com/ytchen175/image/blob/master/model1i.jpg)

Confusion Matrix: \
![image](https://github.com/ytchen175/image/blob/master/model1.jpg)
 
-----------------------------------------------------
### Model2 : SMOTE (catboost) 

Precision of model：0.2232067679724149

Recall of model：0.9359448554135844

F1_score of model：0.36045194082035675

F1_score of model in test set : 0.5779512681

*****

Feature Importance: \
![image](https://github.com/ytchen175/image/blob/master/model2i.jpg)

Confusion Matrix: \
![image](https://github.com/ytchen175/image/blob/master/model2.jpg)

___

### Model3 : SMOTE + ENN (catboost) 

Precision of model3 (SMOTEENN)：0.20853870955786977

Recall of model3 (SMOTEENN)：0.9460322797579018

F1_score of model3 (SMOTEENN)：0.3417448604658225

F1_score of model in test set : 0.5594162267

*****

Feature Importance: \
![image](https://github.com/ytchen175/image/blob/master/model3i.jpg)

Confusion Matrix: \
![image](https://github.com/ytchen175/image/blob/master/model3.jpg)

-----------------------------------------------------
### Model4 : Nearmiss (catboost) 

Precision of model：0.014008954876725073

Recall of model：0.9720914593140552

F1_score of model：0.027619875610245436

F1_score of model in test set : 0.06626493597

*****
