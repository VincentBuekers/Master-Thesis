# A Support Vector Machine embedded Random Forest model
## Large-scale applications

This is a model framework for SVM classification and regression that attempts to reduce the training time of support vector machines.

In libsvm the computational complexity ranges between  O(d x n^2) and O(d x n^3), where d=dimesion of input space and n the number of training samples.

To that end, an extremely randomized decision tree is implemented to partition the data into subsets. That is, in each tree the leaf nodes correspond to a data partition. SVM training and testing is then conducted on the subsamples. This approach is then generalized by means of an ensemble of SVM embedded trees.
