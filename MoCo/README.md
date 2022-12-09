# Problem Statement 

(a) Consider the CIFAR-10 dataset (https://www.cs.toronto.edu/~kriz/cifar.html).
Construct a CNN-based classifier (call it the base-model) and report
the accuracy. Now change the definition of the classes in two different ways (one binary classification problem and one 5-class classification problem). Use the pretrained base-model with an additional
classification head at the last layer in accordance to the new class
definitions. Retrain only the final classification heads and report the
accuracies. Plot the t-SNE graphs for all three cases and record your
observations.

(b) Implement MOCO for CIFAR 10. Consider 5 different types of augmentations (rotations, blur, color distortion, cropping and resizing)
for defining the positive samples. Use the entire training data to learn
the representations. Once the representations are learned, use a linear and logistic layers and retrain with 10-50% of supervised training
data and compare the results with the base CNN model in question
(a). Experiment with two different sizes for the encoder dictionary.
