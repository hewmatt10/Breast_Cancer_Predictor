## Breast Cancer Predictor

This program attempts to model one's likelihood of having breast cancer with a neural network.

The dataset is used from scikit-learn: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

There are a total of 30 input parameters describing the tumor.

The model had:

* 3 hidden layers
  * 300 in the first hidden layer with an activation of relu
  * 60 in the second hidden layer with an activation of relu
  * 30 in the third hidden layer with an activation of relu
* Output layer with 1 neuron with an activation of sigmoid
* BinaryCrossentropy loss computer
* Adam optimizer
* Learning rate of `5e-5`
* 100 epochs

The results of the model was that it had a 94.7% accuracy with predicting a patient's likelihood of having breast cancer. Although the model predicts the likelihood of having breast cancer to a resonably high degree of accuracy, a 94.7% accuracy is still prone to error and not ready for clinical use.

