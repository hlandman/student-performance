# Predicting Student Performance in Portugal

Data from Student Performance Data Set http://archive.ics.uci.edu/ml/datasets/student+performance

In this study, we built a model to predict final grades of Portuguese students in Mathematics. In Portugal,
students receive a final grade using a 20-point scale, where 20 is the highest score. The dataset contained
30 predictor variables including students’ demographics family background and behaviors. We decided to
exclude the first and second trimester scores (“G1” and “G2” variables)in order to narrow down the prediction
to factors outside of scoring itself.

The model predicts student performance based on two different scales:
1. Final Grade (G3-Continuous) using Least Squares and Regularization Regression techniques
2. Pass/Fail (G3-Binary) using Logistic regression & NeuralNets
