# credict_card_fraud_detection
 信用卡盜刷偵測
 
 資料集： https://1drv.ms/u/s!AncGuDALBvHvgqFbM2THRmI4RzvEkA?e=4fKdxW
 
 直接使用catboost(model) test f1-score: 0.7945589782
 Precision of model(raw)：0.7470067673086934
 Recall of model(raw)：0.7237726967047747
 F1_score of model(raw)：0.7352062163777645
 -----------------------------------------------------
 經過SMOTE(model2) test f1-score: 0.5779512681
 Precision of model2(SMOTE)：0.2232067679724149
 Recall of model2(SMOTE)：0.9359448554135844
 F1_score of model2(SMOTE)：0.36045194082035675
 -----------------------------------------------------
 經過SMOTEENN(model3) test f1-score：0.5594162267
 
 -----------------------------------------------------
 經過nearmiss(model4) test f1-score：0.06626493597
 
