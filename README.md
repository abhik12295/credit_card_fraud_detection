## Credit Card Kaggle Anomaly (Fraud) Detection
##### Used Linear Regression Model and after Isolation Forest Method 
##### The IsolationForest ‘isolates’ observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature. Since recursive partitioning can be represented by a tree structure, the number of splittings required to isolate a sample is equivalent to the path length from the root node to the terminating node.
##### This path length, averaged over a forest of such random trees, is a measure of normality and our decision function.<br>
##### Random partitioning produces noticeably shorter paths for anomalies. Hence, when a forest of random trees collectively produce shorter path lengths for particular samples, they are highly likely to be anomalies. <br>

##### Isolation Forest has a 99.74% more accurate than Linear Regression of 93.4%.<br>
##### So overall Isolation Forest Method performed much better in determining the fraud cases.<br>
##### We can also improve on this accuracy by increasing the sample size or use deep learning algorithms however at the cost of computational expense.We can also use complex anomaly detection models to get better accuracy in determining more fraudulent cases.<br>
