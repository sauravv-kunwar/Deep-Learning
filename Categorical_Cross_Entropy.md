## Categorical Cross-Entropy

Categorical cross-entropy is a loss function for **multi-class classification**. It compares the true class labels (usually one-hot encoded) with the model's predicted class probabilities, often produced by a softmax output layer. The loss is low when the model assigns high probability to the correct class and high when it does not.

Use **sparse categorical cross-entropy** instead when class labels are represented as integer class IDs rather than one-hot vectors.
