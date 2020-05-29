# Forest-Cover-Type-Prediction
In this work forest cover type (the predominant kind of tree cover) from strictly cartographic variables 
(as opposed to remotely sensed data) has to be predicted. The actual forest cover type for a given 30 x 30 
meter cell was determined from US Forest Service (USFS) Region 2 Resource Information System data. Independent
variables were then derived from data obtained from the US Geological Survey and USFS.


The main highlights of the work are as follows:
1. load data
2. Disriptive Analysis of data.
3. stacked 4 wilderness area columns into one column which has 4 different wilderness area.
4. stacked 40 soil types columns into one column which has 40 different soil types.
5. Univariate, Bivariate and Multivariate Analysis on given features.
6. Outlier detection
7. Skewness detection
8. Handling Outliers by binsurization method and Skewness by transformation.
9. Standardization of data
10. Base Model (Logistic Regression)
11. Implement Decision Tree and KNN models and finding accuracy.
12. Feature Extraction: (i) Aspect_direction
                        (ii) Mean_Distance_Hydrology_To_Fire_Points
                        (iii) Mean_Distance_Hydrology_To_Roadways
                        (iv) Mean_Distance_Roadways_To_Fire_Points
                        (v) Mean_Distance_Hydrology_and_Roadways_To_Fire_Points
                        (vi) Mean_Distance_Hillshades
13. Moelling with extracted features:(i)    "KNN",
                                     (ii)   "RandomForest",
                                     (iii)  "DecisionTree",
                                     (iv)   "SVC",
                                     (v)    "Gaussian naive",
                                     (vi)   "Bagging Classifier",
                                     (vii)  "GradientBoosting",
                                     (viii) "AdaBoost Classifier",
                                     (ix)   "XGBOOST Classifier",
                                     (x)    "Voting Classifier
14. Feature selection using feature importance matrix of rendom forest and implement all 10 models.
15. Random forest and Bagging are chosen best classifier for the given dataset with high accuracy, cohen kapp score and MCC value.
16. PCA can also be applied and check with all models but as data do not have any multicolinearity so PCA will not be a good choice.
17. For Balancing the data SMOTE can be implemented.
