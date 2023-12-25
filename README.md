CNN-Project

This project utilizes a Convolutional Neural Network (CNN) implemented in TensorFlow and Keras to classify images as either cats or dogs. The dataset consists of labeled images for training and testing, and the model is trained to learn features that distinguish between the two classes.

Directory Structure
- dataset/training_set: Training images, organized into subdirectories for cats and dogs. 
- dataset/test_set: Testing images, similarly organized into subdirectories.

Implementation

- Data Augmentation: Training images undergo augmentation (shearing, zooming, and horizontal flipping) to enhance model robustness.
- Model Architecture: The CNN consists of convolutional layers, max-pooling layers, and dense layers for feature extraction and classification.
- Training: The model is trained using the augmented training set with binary classification objectives (cat or dog). 
- Evaluation: Model performance is assessed on the test set to measure accuracy and loss.

Prediction

A single image (cat_or_dog_1.jpg) is used for a demonstration: 
- The image is loaded, preprocessed, and fed into the trained model for prediction. The result is interpreted using class indices, determining whether the image depicts a cat or a dog.