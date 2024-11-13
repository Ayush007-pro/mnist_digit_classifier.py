## README

### Project Title: MNIST Digit Classifier (using TensorFlow)

#### Overview
This project demonstrates how to build a simple neural network using TensorFlow and Keras to classify handwritten digits from the MNIST dataset. The model is a Sequential neural network that is trained and tested on the MNIST data to achieve digit recognition with a high accuracy.

#### Requirements
- Python 3.x
- TensorFlow 2.x
- Matplotlib

#### Installation
1. Install the required libraries:
   ```bash
   pip install tensorflow matplotlib
   ```

2. Save the code file as `mnist_digit_classifier.py`.

#### Usage
1. Run the code file using Python:
   ```bash
   python mnist_digit_classifier.py
   ```
2. The code will load and preprocess the MNIST data, display an example image from the dataset, train a neural network model, and save the trained model.
3. It will also print the model's accuracy on the test set before and after loading the saved model.

#### Model Structure
The model consists of:
1. **Flatten Layer**: Transforms each 28x28 image into a 784-dimensional vector.
2. **Dense Layer (128 units)**: A fully connected layer with ReLU activation for non-linearity.
3. **Dense Output Layer (10 units)**: A fully connected layer with Softmax activation to classify each image as one of the 10 digits (0-9).

#### Files
- `mnist_digit_classifier.py`: Contains the code to preprocess the data, train the model, evaluate it, and save the trained model.
- `my_mnist_model`: Saved trained model that can be reloaded for evaluation.
