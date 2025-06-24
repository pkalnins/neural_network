## Classification of Liver Disease via a Neural Network
A project that builds a neural network (using only core Python libraries) for classifying patients liver disease

### Project Overview
The objectives of this project are as follows:

**Objective 1**: Build a neural network (multilayer perceptron) in Python

- Use only base python packages (numpy, pandas, matplotlib)
- Allow for hyperparameter tuning (see list of hyperparameters below)
- Compare results to Scikit Learn MLP package

**Objective 2**: Use the network for classification

- Data: Indian Liver Patient Dataset
- 10 features (liver biomarkers)
- Binary outcomes: liver disease or no liver disease

#### Desired hyperparameters:
**Adjustable**:

- Network architecture: be able to specify number of layers and nodes in each layer
- Learning rate
- Activation functions: be able to specific either sigmoid, tanh, relu for hidden activations
- Training epochs
- Classification threshold: adjustable, based on training class imbalance
- Training batch size

**Consider**:

- Class imbalance in the data
- Adding L1 regularization
- Early stopping with validation set

**Evaluation Metrics**:

- Accuracy
- Precision, recall, f1-score
- Confusion matrix
- Plot training and validation costs per epoch
