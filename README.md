# credict_card_fraud_detection
 信用卡盜刷偵測
 
 資料集： https://1drv.ms/u/s!AncGuDALBvHvgqFbM2THRmI4RzvEkA?e=4fKdxW
 
 直接使用catboost(model) test f1-score: 0.7945589782
 
 Precision of model(raw)：0.7470067673086934
 
 Recall of model(raw)：0.7237726967047747
 
 F1_score of model(raw)：0.7352062163777645
 
 Feature Importance:
 ![image](https://github.com/ytchen175/image/blob/master/model1i.jpg)
 
 PCA:
 ![image](https://github.com/ytchen175/image/blob/master/pca1.jpg)
 
 Confusion Matrix:
 ![image](https://github.com/ytchen175/image/blob/master/model1.jpg)
 
 -----------------------------------------------------
 經過SMOTE(model2) test f1-score: 0.5779512681
 
 Precision of model2(SMOTE)：0.2232067679724149
 
 Recall of model2(SMOTE)：0.9359448554135844
 
 F1_score of model2(SMOTE)：0.36045194082035675
 
 Feature Importance:
 ![image](https://github.com/ytchen175/image/blob/master/model2i.jpg)
 
 PCA:
 ![image](https://github.com/ytchen175/image/blob/master/pca2.jpg)
 
 Confusion Matrix:
 ![image](https://github.com/ytchen175/image/blob/master/model2.jpg)
 
 -----------------------------------------------------
 經過SMOTEENN(model3) test f1-score：0.5594162267
 
 Precision of model3 (SMOTEENN)：0.20853870955786977
 
 Recall of model3 (SMOTEENN)：0.9460322797579018
 
 F1_score of model3 (SMOTEENN)：0.3417448604658225
 
 Feature Importance:
 ![image](https://github.com/ytchen175/image/blob/master/model3i.jpg)
 
 PCA:
 ![image](https://github.com/ytchen175/image/blob/master/pca2.jpg)
 
 Confusion Matrix:
 ![image](https://github.com/ytchen175/image/blob/master/pca3.jpg)
 
 -----------------------------------------------------
 經過nearmiss(model4) test f1-score：0.06626493597
 
 Precision of model4 (NearMiss)：0.014008954876725073
 
 Recall of model4 (NearMiss)：0.9720914593140552
 
 F1_score of model4 (NearMiss)：0.027619875610245436
