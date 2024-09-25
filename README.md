# NeuralNetworkTitanic

This assignment involves building a neural network from scratch (manually implemented without Keras) to classify Titanic passengers based on whether they survived or not. The dataset consists of two files, `train.csv` and `test.csv`, which contain the training and test data, respectively. A detailed description of the dataset and the research objective can be found at [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic).

## Dataset

- `train.csv`: Contains the training data with features about Titanic passengers and the target variable (`Survived`).
- `test.csv`: Contains the test data where predictions need to be made.

## Task Breakdown

### Neural Network Model

**Goal:**
- Train a neural network to classify passengers as survivors or non-survivors based on the available features.

### Neural Network Details:
- The neural network is manually implemented using matrix operations, without using the Keras or TensorFlow libraries.
  
### Steps:

1. **Data Preparation:**
   - Clean and preprocess the data, handling missing values, encoding categorical variables, and scaling/normalizing the features as needed.

2. **Neural Network Architecture:**
   - Implement a neural network manually in matrix form. This involves:
     - Initializing weights and biases.
     - Defining the forward pass, including matrix multiplication and activation functions.
     - Implementing the backpropagation algorithm to update weights using gradient descent.
     - Using appropriate loss functions for binary classification (e.g., binary cross-entropy).

3. **Model Training:**
   - Train the neural network on the training data (`train.csv`).

4. **Model Evaluation:**
   - Evaluate the performance of the trained neural network on the test set (`test.csv`) and report the accuracy.

5. **Prediction:**
   - Use the trained neural network to predict survival on the test data and save the results for evaluation or submission to Kaggle.

