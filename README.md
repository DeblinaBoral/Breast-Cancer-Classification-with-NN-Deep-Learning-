# Breast-Cancer-Classification-with-NN-Deep-Learning-
The Breast Cancer Classification model leverages deep learning techniques to classify breast cancer tumors as malignant or benign using a neural network model. Accurate classification is crucial for early detection and treatment planning.
**Project Overview**
**Objective**: Develop a neural network to accurately classify breast cancer tumors based on diagnostic data.

**Model Architecture**: Implemented a neural network with:

- An input layer of 30 neurons
- Two hidden layers with 16 and 8 neurons, respectively
- An output layer with a single neuron for binary classification
- Activation Functions: Employed ReLU for hidden layers and Sigmoid for the output layer.

**Performance:**

- Accuracy: Achieved 98% on the test set
- Precision: 97%
- Recall: 98%

**Highlights**

- Data Preprocessing: Performed feature scaling using StandardScaler to normalize the data.
- Model Training: Trained over 100 epochs with a batch size of 32, utilizing the Adam optimizer and binary cross-entropy loss function.
- Evaluation: Used confusion matrix and ROC-AUC curve to assess model performance.

**Results**
The neural network demonstrated high accuracy and robustness in classifying breast cancer tumors, indicating its potential as a decision-support tool in clinical settings.
