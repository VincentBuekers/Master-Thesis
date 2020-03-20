# Master of Statistics: Thesis
## A Support Vector Machine embedded Random Forest model for large scale applications

This is a model framework for SVM classification and regression on large scales. In order to reduce the SVM training time (O(n^2)), an extremely randomized forest is implemented to partition the data into subsets by way of the resulting leaf nodes. The SVMs are then trained on these smaller subsamples.
