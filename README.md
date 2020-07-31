# Somerville-Happiness-Survey
Supervised models to predict the happiness by entering categorical features as input

Somerville Happiness Survey data set [1] was selected to be used in this project. This data set was collected in 2015 by surveying 143 Somerville residents about their personal happiness and their satisfaction with city services. There are 6 attributes X1 to X6 with values 1 to 5 and a binary decision attribute as follows:

• D = decision attribute (D) with values 0 (unhappy) and 1 (happy)<br/>
• X1 = the availability of information about the city services<br/>
• X2 = the cost of housing<br/>
• X3 = the overall quality of public schools<br/>
• X4 = your trust in the local police<br/>
• X5 = the maintenance of streets and sidewalks<br/>
• X6 = the availability of social community events<br/>
No missing values have been observed in this data set, so no further action is needed to deal with
them.

In this project Decision Tree, Bagging, Random Forest and Gradient Boosting methods were used for training classification model to predict happiness or unhappiness.



**Models**<br/>
Decision trees provide a hierarchical representation of the data that can be used for classification
and regression problems. They are easy to interpret, extremely fast and can handle categorical input
data. However, they are prone to overfitting and a small change in data can lead to a large change in
tree structure. In order to remedy these issues, ensemble methods can be used.
Bootstrap aggregating or Bagging is an ensemble method which can be applied to decision tree
method to improve the stability and accuracy. It works by several sampling of data with
replacement, and ended up with an ensemble of different decision tree models which the average of
their predictions will indicate the final result.
Random Forest is an extension of Bagging that in addition to taking random sample of data, it also
uses random subset of features which mitigates overfitting.
Gradient Boosting is another ensemble technique which is an extension of Boosting method.
Boosting itself is an ensemble method having ensemble of trees in which each tree tries to minimize
the error by considering the previous tree. Gradient Boosting technique minimizes errors by
gradient descent algorithm.

[1] Koczkodaj, W.W.; Li, F.; Wolny-Dominiak, A., RatingScaleReduction package: stepwise
rating scale item reduction without predictability loss, R JOURNAL, 10(1): 43-55, 2018.
