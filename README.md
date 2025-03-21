# Fruits-360-dataset

Dataset: https://www.kaggle.com/datasets/moltean/fruits/data

This assignment focuses on building a convolutional neural network (CNN) model using the Fruits 360 dataset to classify various fruit images. The objective is to implement an accurate image classification model while following best practices such as data augmentation, dropout layers, and model evaluation.


We built a Convolutional Neural Network (CNN) to classify images from the Fruits 360 dataset. We worked specifically with the original-size branch, which contained 20,676 images across 37 classes of fruits, vegetables, and nuts. After loading the dataset, we applied data augmentation techniques including rotation, zoom, shear, and horizontal flipping to improve model generalization. Our CNN architecture consisted of three convolutional layers (32, 64, and 128 filters) with batch normalization, max pooling, and increasing dropout rates (0.2 to 0.5) to prevent overfitting. The model was compiled using categorical cross-entropy loss and trained for 100 epochs. Performance evaluation showed excellent results with a test accuracy of 96%. We visualized the model's performance through accuracy/loss curves, confusion matrices, and examples of incorrect predictions to better understand the model's strengths and limitations.


