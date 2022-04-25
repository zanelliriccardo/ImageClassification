# Image Classification

Goal: classify images of leafs (like the ones in the example image below), which are divided into categories according to the species of the plant to which they belong. 
Being a classification problem, given an image, the goal is to predict the correct class label.

The problem is a multiclass classification problem. Thus, you must provide for each image in the test set the corresponding predicted class.

Only the training set is given. The test set is not provided. You must submit directly your code for evaluation.
The metric used to evaluate models is the Mean Accuracy. The score is computed as:

MeanAccuracy = Σ1≤i≤N(predictions_i == targets_i) / N , where N is the total number of images in the test set

Performance:

MeanAccuracy = 0.88

<p align="left">
  <img src="fine_tuned_model.png" width="800">
</p>