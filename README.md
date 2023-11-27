# red-wine-quality-classification
## red wine quality dataset source: https://archive.ics.uci.edu/dataset/186/wine+quality 

# Abstract
This study delves into the classification of red wine quality, focusing on Vinho Verde samples sourced from the northern region of Portugal. The dataset comprises 1599 wine entries, encompassing 12 numeric features without any missing values. All values are numeric. The input values including fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur-dioxide, density, pH, sulphates, and alcohol content are float and only output value (wine quality) is integer. 

Initial analysis involved the creation of a correlation map, facilitating the understanding of the relationships between different features by computing their covariances. There are some serious outliers in the residual sugar, free sulfur dioxide and total sulfur dioxide columns. Outliers that are above three standard deviations from the mean of these columns are removed.

The PyCaret library was employed to explore and select the optimal classification model for the dataset. Some common performance metrics for classification problem have been used to evaluate the performance of these models, such as Accuracy, Precision, Recall, F1 score and area under the receiver operating characteristic curve (AUC-ROC). Among several models, the Extra Trees Classifier emerged as the most effective, achieving a 59% accuracy rate in classifying wine quality on a scale of 0-10. Additionally, both the Random Forest Classifier and the CatBoost Classifier exhibited commendable accuracy in this classification project. Despite the dataset is imbalanced, these models demonstrate promising accuracy rates, offering valuable insights into potential applications within the wine industry for quality assessment purposes.

# Youtube link: https://youtu.be/0m0_b-7F83M
