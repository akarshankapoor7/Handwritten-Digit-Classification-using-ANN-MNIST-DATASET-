The goal of this project was to develop an Artificial Neural Network (ANN) model capable of accurately classifying handwritten digits from the MNIST dataset. The MNIST dataset consists of 60,000 grayscale images of handwritten digits (0-9), each sized 28x28 pixels.

Key Steps:
Data Preparation: The dataset was loaded and preprocessed by normalizing pixel values and flattening the images into 784-dimensional vectors. It was then split into training (60,000 images) and testing (10,000 images) sets.

Model Architecture: An ANN was designed with an input layer of 784 neurons, two hidden layers with ReLU activation functions, and an output layer with 10 neurons using softmax activation for multi-class classification.

Training: The model was trained using the Adam optimizer and categorical cross-entropy loss, with monitoring of validation accuracy to prevent overfitting.

Evaluation: The model was evaluated on the test set, achieving a high accuracy rate (often above 98%), demonstrating its effectiveness in digit classification.

Results: The trained model successfully predicted unseen handwritten digits, showcasing the capability of ANNs to learn from and generalize on image data.

This project highlights the application of neural networks in computer vision tasks and serves as a foundational exploration into more advanced architectures and techniques in deep learning.
