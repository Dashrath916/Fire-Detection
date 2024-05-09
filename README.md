Fire Detection with CNN
Project Overview
This project aims to build a Convolutional Neural Network (CNN) model to detect fire in images. The model identifies images containing fire or smoke and labels them accordingly.

Dataset
The dataset consists of images with and without fire. It has been split into training and testing sets. Data augmentation is used to enhance training.

Model Architecture
The CNN model comprises:

Convolutional Layers: Two layers with 32 and 64 filters, respectively.
Pooling Layers: Max pooling with 2x2 pool size.
Fully Connected Layer: 128 units with ReLU activation.
Output Layer: 1 unit with sigmoid activation for binary classification.
Model Training
Optimizer: Adam
Loss Function: Binary cross-entropy
Metrics: Accuracy
Epochs and Batch Size: Configured based on dataset size
Predictions and Visualization
For testing, the model predicts whether a given image contains fire. If it does, the label "Fire" is added to the image.

Challenges and Solutions
Data Imbalance: Addressed with data augmentation and balanced datasets.
Overfitting: Mitigated with early stopping and dropout layers.
Model Complexity: Simplified for efficiency and robustness.
Results
The model achieves satisfactory accuracy on the test set, demonstrating its ability to detect fire in images.

Repository Contents
Python script for the model and training
Trained model weights
Example predictions
README.md
Conclusion
This project successfully creates a fire detection model using a CNN, offering potential applications in safety and security.
