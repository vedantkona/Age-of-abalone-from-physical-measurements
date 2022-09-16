# Age-of-abalone-from-physical-measurements

We have used different Classification algorithms such as K-nearest neighbors, Random Forest Classifier, and Support vector machine to implement this prediction system. In KNN some prior data (also called training data) classifies coordinates identified by an attribute. Now given another set of data points also called testing data, allocate these points to a group by analyzing the training set. Then an unclassified point is assigned to a group by observing what group its nearest neighbors belong to. 
In Random Forest it selects data points from a training set and each data point is given a decision tree. Then each decision tree produces a prediction result, and then on a majority basis, the random Forest Classifier predicts the final decision.
On the other hand, it performs internal testing on 2/3rd of the available training data to assess the accuracy of the model.

MLPClassifier stands for Multi-layer Perceptron classifier which in the name itself connects to a Neural Network. Unlike other classification algorithms such as Support Vectors or Naive Bayes Classifier, MLPClassifier relies on an underlying Neural Network to perform the task of classification.
