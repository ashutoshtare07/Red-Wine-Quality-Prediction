# Red-Wine-Quality-Prediction
In this repo I have used three different machine learning models to predict the quality of Red WINE
The models used in this repo were K-Nearest Neighbour, Random Forest and Logistc Regression 
Each of these models have produced different accuracy score 

1)K-Nearest Neighbour : 0.6188

2)Random Forest : 0.6906

3)Logistic Regression : 0.5906


Let us now discuss how each of these model works :

1) K-Nearest Neighbours
   Store all data – KNN doesn't learn anything, it just memorizes all the training data.
   Measure distance – When a new point comes in, it measures the distance to every stored point.
   Find K nearest neighbors – It picks the K closest points (e.g., if K=3, it picks the 3 closest).
   Take a vote – Whichever label appears most among those K neighbors wins.
   That's the prediction! – The new point gets assigned that winning label.

2) Random Forest
   Build many decision trees – It creates hundreds of different decision trees, each trained on a random subset of the data.
   Random features too – Each tree also gets a random set of features to split on, making every tree slightly different.
   Each tree makes a prediction – Every tree independently gives its own answer.
   Take a vote – All trees vote, and the majority answer wins (for classification) or average is taken (for regression).
   That's the prediction! – The final answer comes from the crowd of trees, which is more accurate and reliable than any single tree alone.

3) Logistic Regression
   It predicts probability – Unlike linear regression, it predicts the probability of something being YES or NO (e.g., will a customer churn? 0 to 1).
   Uses the S-curve (Sigmoid) – It squishes any number into a value between 0 and 1 using an S-shaped curve.
   Draws a decision boundary – It finds a line that best separates the two classes (e.g., spam vs. not spam).
   Applies a threshold – If probability > 0.5 → predict YES, if < 0.5 → predict NO.
   Learns by minimizing errors – It adjusts its internal weights during training to make the most correct predictions possible.


