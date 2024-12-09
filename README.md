Fraudulent financial transacHons pose a significant challenge to financial insHtuHons, leading to
substanHal monetary losses and reputaHonal damage. The increasing volume of digital transacHons has
intensified the need for sophisHcated fraud detecHon systems. This project, Htled Fraud Detec+on in
Credit card Transac+ons Using Machine Learning, aims to address these challenges by developing an
accurate and eﬃcient fraud detecHon model.
Using a publicly available dataset from Kaggle, which contains both legiHmate and fraudulent credit card
transacHons, the project explores various machine learning and tradiHonal algorithms to detect
fraudulent acHvity. The dataset presents an inherent challenge due to its highly imbalanced nature, with
fraudulent transacHons represenHng a small fracHon of the total data.
The project involves comprehensive data exploraHon, preprocessing, and feature engineering to
opHmize the input for machine learning models. Techniques such as SyntheHc Minority Oversampling
(SMOTE) and class-weight adjustments are used to handle data imbalance. MulHple models, including
LogisHc Regression, Random Forest, Gradient BoosHng Machines (XGBoost), Support Vector Machines
(SVM), Neural Networks, K-Nearest Neighbor classificaHon and Anomaly DetecHon techniques, are
evaluated.
Key findings indicate that the K-Nearest Neighbors (KNN) model achieved the highest recall (98%) and
ROC-AUC (99%), demonstraHng its excepHonal capability to detect fraudulent transacHons while
maintaining strong precision. The Neural Network model also performed well with a high recall (91.8%)
and ROC-AUC (99.1%), eﬀecHvely idenHfying fraud with high precision (87.6%). AddiHonally, XGBoost
and SVM (RBF) showed good performance, balancing precision and recall eﬀecHvely.
KNN performs beEer in fraud detecHon because it captures localized paierns and is less prone to
overfijng, especially with imbalanced datasets. It excels at detecHng fraud clusters based on proximity
in the feature space. In contrast, Neural Networks may struggle with overfijng, require more data, and
face challenges in learning subtle fraud paierns, parHcularly when data is imbalanced.
In conclusion, the project emphasizes the importance of selecHng models based on business objecHves,
such as maximizing fraud detecHon or minimizing false posiHves. The findings oﬀer valuable insights for
implemenHng scalable fraud detecHon systems that can be applied to high-volume transacHon
environments.
