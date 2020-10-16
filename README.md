# Tianchi-competition-loan-default

Competition link：https://tianchi.aliyun.com/competition/entrance/531830/introduction

Ranking list link： https://tianchi.aliyun.com/competition/entrance/531830/rankingList

Current Ranking: 17/2756

Name of Contestants: 萌新求组队

Organization： Duke University

Major Work: 
* Built up xgb,lbg,catboost and neuro-network models and fine-tuned params, single catboost model performed best with test_AUC=0.7388
* Applied different preprocessing strategies for different boosting models (xgb,lbg,catboost)
* Utilized **target encoding** technics to extract informaion from **high-cardinality categorical features** (>100 distinct values) (regioncode,employmentTitle,postCode,etc.)  
Reference: [A Preprocessing Scheme for High-Cardinality Categorical Attributes in Classification and Prediction Problems](https://dl.acm.org/doi/10.1145/507533.507538)
* Model fusion with empirical weights based on valid_AUC performances, induced test_AUC increasing from 0.7388 to 0.7397)

