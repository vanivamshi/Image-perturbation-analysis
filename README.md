# Image-perturbation-analysis

Evaluate the robustness and reliability of computer vision. It involves systematically modifying or perturbing images and then observing how these changes affect the model's predictions. The goal is to understand how sensitive a model is to small changes in the input data and to identify any weaknesses in its ability to generalize beyond the training data
1) Uses MNIST dataset
2) Gaussian noise and Gaussian blur are added partly to the training and testing dataset
3) MobileNetV2 part of OpenCV is used to study the tarin dataset
4) L2 regularization prevents overfitting by penalizing large weights
