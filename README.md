# Sign Language Digits Recognition

A neural network implementation for recognizing hand sign digits (0-9) using NumPy, built as part of the Fundamentals of Deep Learning course.

## Dataset
- 5,000 grayscale images (28x28 pixels) of hand signs representing digits 0-9
- 500 images per class
- Pixel values range: 0-255
- Format: NumPy arrays (images) with corresponding labels

## Implementation Features
- Built using pure NumPy (no deep learning frameworks)
- Binary classifier focusing on two selected digits
- Feed-forward neural network with:
  - Input layer (784 nodes)
  - Hidden layer (configurable size)
  - Output layer (1 node)
- Sigmoid activation function
- Binary Cross-Entropy loss
- Gradient descent optimization

## Model Architecture
```python
input_layer = 784  # 28x28 flattened
hidden_layer = # configurable
learning_rate = # configurable
epochs = # configurable
```

## Key Components
- Data preprocessing
- Feature scaling (0-1 normalization)
- Train/test split (80/20)
- Forward propagation
- Backpropagation
- Weight updates
- Performance visualization
- Confusion matrix evaluation

## Usage
1. Load the dataset (`dataset_labels.npz`)
2. Configure hyperparameters
3. Train the model
4. Evaluate on test set
5. Visualize results

## Requirements
- NumPy
- Matplotlib
- scikit-learn (for utilities)
- Google Colab (recommended environment)

## Authors
- Ofir Almog 
- Adir Edri

## Course Information
Mid-semester assignment Part 1 - Basics of Deep Learning
