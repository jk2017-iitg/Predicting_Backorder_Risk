# Predicting-Backorder-Risk-and-Optimizing-Profit-

Training dataset - https://drive.google.com/file/d/1yMp_Fbi36jqn1F2iUayYO0K3c0iATum8/view?usp=sharing

Problem statement - A hypothetical manufacturer has a data set that identifies whether or not a backorder has occurred. The challenge is to accurately predict future backorder risk using predictive analytics and machine learning.

Model used - The training set being an imbalanced dataset wrt to the target variable, the method of synthetic minority oversampling technique was applied so that those 0.25% of products which were getting backorders can be predicted. Here we have used H2O automated ML algorithm, which is a professional grade machine learning algorithm.

Result obtained - AUC of 0.92 was acheived on the test set.
