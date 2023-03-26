# Deep Learning: Getting Started.
# [*Course Certificate*](https://www.linkedin.com/learning/certificates/f6fb732520ece7c0acebd154d7650ca1210ea8104e77c401686219fba9f526ab)

### Introduction to Deep Learning:
- Used Keras and Tansorflow for implementation. 
- Used anaconda and jupyter notebook. 
- What is Deep Learning: 
    - Subset of ML.
    - Neural networks with three more layers.
    - Imitates how humans process data and make decisions.
    - Exponential growth in the last few years.
    - Powered by advances in large-scale data processing and inference.
    - Pupular in NLPs, speech recognition and synthesis, image recognition, self-driving card, customer experience, healthcare, and robotics.
- Linear Regression: 
    - Linear model.
    - Relationship between two or more variables.
    - Predict dependent variable based on independent variable.
    - Slope and intercept models the relationship.
    - Example: 
        - Find values for slope and intercept.
        - Use known values of x and y.
        - Multiple independent variables make it complex.
        - If there are more independent variables, then it is difficult. 
    - Logistic Regression: 
        - A binary model.
        - Relationship between two or more variables.
        - Output is 0 or 1. 
        - There is an Activation Function = f.
- Analogy: 
    - Complex and iterative process.
    - Starts with random initialization and works towards the right values by trial and error.
- The perceptron: 
    - Is an algorithm for supervised learning for binary classification.
    - Resembles a cell in the human brain.
    - A single cell neural network.
    - Based on logistic regression.
    - Derive the formula => Perceptron. 
- ANN (Artificial Neural Network): 
    - A network of Perceptrons, modeled after human brain.
    - Perceptron are called nodes in the neural network.
    - Nodes organized as layers.
    - Each node has weight, biases and activation functions.
    - Each node is connected to all nodes in the next layer.
    - It has Input layer, Hidden layer, Output layer. 
    - How ANN works?
        - Input (indpendent variables) are sent from the input layer.
        - Input passed on to the nodes in the next hidden layer.
        - Each node computes its output based on its weights, biases, and activation functions.
        - Nodes output is then passed on as inputs to the next layer.
    - Training an ANN: 
        - Model is represented by parameteres and hyperparameters: weight, bias. 
        - Training Process: 
            - Use training data(known values of inputs and outputs).
            - Create network architecture with intuition.
            - Start with random values for weights and biases.
            - Minimize error in predicting known outputs from inputs. 
            - Adjus weight and biases until error is minimized.
### Neural Network Architecture:
- The Input Layer: 
    - Vectors: input to deep learning is a vector of numeric values. 
    - Samples = Rows and Features = Columns
    - Input Preprocessing:
        - Numeric = Centering and scaling.
        - Categorical = Integer encoding, one-hot encoding.
        - Text = TF-IDF, embeddings.
        - Image = Pixels, RGB representation.
        - Speech = Time series of numbers. 
- Hidden Layers: 
    - Range of nodes is 2n.
    - More nodes and layers = more resources => AWS.
- Weights and biases: 
    - Made as Matrices.
    - Matrix multiplication. 
- Activation Functions: 
    - Take input and process to get output based on input values. 
- Output Layer: 
    - Only one layer of output produces desired Y. 
    - Has its own weights and biases.
### Training a Neural Network:
- Setup and Initialization. 
- Input Preprocessing. 
- Splitting Input:
    - Training set: used to fit the parameters
    - Validation set: used for model selection/tuning.
    - Test set: used to measure the final model performance.
    - Usual split: 80:10:10
- Forward Propagation: 
    - Inputs, Targets, and Predictions. 
    - Compare Error rates.
- Measure accuracy error: 
    - Loss function: measures the prediction error for a single sample.
    - Cost function: measures the error across  a set of samples.
        - MSE (Mean Square Error) => Regression.
        - RMSE (Root Mean Square Error) => Regression
        - Binary cross Entropy. => Binary classification.
        - Categorical Cross Entropy. => Multi-class classification.
    1. Send a set of samples through the ANN and predict outcome.
    2. Estimate the prediction error between the prediced outcome and expected outcome using a cost function. 
    3. Use back propagation to adjust weights based on the error value. 
- Back Propagation: 
    - Each nodes in NN contributes to overall error in prediction. 
    - Works in reveresed order of Forward propagation. 
    - Derive new errors. 
- Cradient Descent: 
    - Repeating Forwared and Backward propagation to reduce error. 
- Batches and Epoch:    
    - Batch: is a set of samples sent through ANN in a single pass. Typical size 2^n. 
    - Epoch: is number of times the entire training set is sent through the ANN and it has one or more batches. 
        - > the training process completes when all epoch is complete.
    - Training set size = 1000, batch size = 128, epoch = 50 ==> batches per epoch = ceil(1000/128) = 8 and total iterations (passes) through ANN = 8*50 = 400. 
    - Bachtes and Epoches are considered hyperparameteres.
- Validation and Testing: 
    - Compare the predictions against its actual parapmeters. 
    - Final step is Evaluation. 
- An ANN Model: 
    1. Parameteres: weights and biases. 
    2. Hyperparameters: number of layers, nodes in each layer, activation function, cost functions, learning rate, optimizers, batch size and epoch. 
        Predictions just like forward and backward propagation. 
### Deep Learning Examples:
- The Iris Classification Problem. 
    - Feature Variables: sepal length, sepal width, petal length, petal width.
    - Terget Class = Sepcies: setosa, versicolor, virginica. 
    - Goal => build an ANN model. 
- Implementation: 
    1. Install dependencies:
        ```!pip install pandas
       !pip install sklearn
       !pip install matplotlib
       !pip install tenserflow```
    2. Prepare input data for deep learning
    3. Create a model. 
    4. Train and Evaluate the model. 
    5. Saving and Loading Models.
    6. Predictions with deep learning
- The Spam Classification Problem: 
    - Feature variables: SMS message.
    - Target class: message type (ham, spam)
    - Build an ANN model to predict message type.
### Deep Learning Exercise:
- Problem: 
    - IT Operations: Root Cause Analysis (RCA)
### Conclusion: 
> Learn more about how to optimize and fine-tune deep learning models. <br.
> Explore CNN and RNN

