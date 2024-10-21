# Ensemble Learning

When it comes to using machine learning algorithms in production level, it is often ill-advised to simply use one model, regardless of how well that model does while testing it. Often in production, we use multiple models together to make a prediction. If there the problem is a classification problem, we use majority vote to decide the class. If it is a regression problem, we average the output of each model to get a final result. This general process is called Ensemble Learning.
There are three techniques in Ensemble Learning. These are:

Boosting: In this technique, each model is trained sequentially as each successive model is trained on the errors of the models before it. The models in a Boosting are generally shallow, under fitted, high bias and low variance decision trees.

Bagging: Unlike boosting, bagging randomly samples the data to get sub-samples and then uses the sub-sample data to train independent models (decision trees) in parallel.
With this technique, each model is often an overfitted, deep decision tree with low bias and high variance. Random forest is a type of ensemble learning using bagging with a twist. Random forest not only samples the data to get sub-samples to train the individual trees but also samples a subset of the features to be used for each decision tree. This ensures that each model is independent, uncorrelated, and focusing on only certain aspect of the data.

Stacking: Similar to bagging, stacking trains independent models in parallel where each model has weak bias and high variance. However, unlike bagging, each model is trained on the full dataset and the base models do not have to be decision trees.
