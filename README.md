# Fully-Connected-Neural-Network-with-Pytorch
**Data Shape:** (60,28,28)

**Flatten Data Shape:** (60,784)

**Hidden Layers:** (784,50)

**Output Layer:** (50,10)

### Categorical Crossentropy Loss Function

The **categorical crossentropy** loss is used for multi-class classification problems and is defined as:

L = - (1 / N) * Σ [Σ y_{i,c} * log(ŷ_{i,c})]

Where:

- N: Number of samples  
- C: Number of classes  
- y_{i,c}: True label for class c of sample i (one-hot encoded)  
- ŷ_{i,c}: Predicted probability for class c of sample i  

The loss is minimized when the predicted probabilities match the true class labels.



![Hidden-Layer-1-1024x603-min](https://github.com/user-attachments/assets/37ad167c-688d-4ffc-8e34-322aedcbe429)
