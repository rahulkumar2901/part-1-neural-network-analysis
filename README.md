# **Task 6: Final Reflection**
#1. What role do weights and biases play in the model?

  Weights and biases are the main learnable parameters of a neural network. Weights determine the importance of input features and control how strongly inputs influence the output. Bias helps shift the activation function and allows the model to fit the data more flexibly. During training, the neural network continuously updates weights and biases using backpropagation and optimization algorithms to reduce prediction error.

 # 2. Why is an activation function required?

 Activation functions introduce non-linearity into the neural network. Without activation functions, the neural network would behave like a simple linear model and would not be able to learn complex patterns from the data. Functions like ReLU and ELU help the network learn meaningful relationships between input features and target variables.

# 3. What happens when learning rate is too high or too low?

  The learning rate controls how much the model updates its weights during training. If the learning rate is too high, the model may overshoot the optimal solution and training may become unstable. If the learning rate is too low, training becomes very slow and the model may take a long time to converge. Therefore, selecting an appropriate learning rate is important for stable and efficient learning.

 # 4. Did your model show signs of underfitting or overfitting?

The model did not show strong signs of overfitting because the training and testing accuracies were very similar. However, the classification report and confusion matrix revealed that the model struggled to correctly identify churn customers due to severe class imbalance in the dataset. This indicates that the main challenge was class imbalance rather than traditional underfitting or overfitting.

