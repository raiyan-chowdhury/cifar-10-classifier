# Image Recognition Model for CIFAR-10 dataset

Created and optimised a convolutional neural network (CNN) architecture for image recognition, made to classify images into 10 distinct classes. The model consisted of blocks of convolutional layers connected in parallel through a multilayer perceptron (MLP).

## Model Architecture

The CNN model consists of the following components:

- **Block**: Two convolutional layers and an MLP for assigning weight values to these layers.
- **Backbone**: Four blocks composing the backbone.
- **Classifier**: An MLP that takes as input the output of the last block for final classification.

## Training Details

- **Loss Function**: Cross-Entropy Loss
- **Optimizer**: Adam
- **Hyperparameters Used**:
  - Learning Rate: 0.0004
  - Batch Size: 64
  - Number of Epochs: 30

Overall, I achieved a final testing accuracy of 86.08% when running the model on a GPU.
