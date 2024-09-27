Histopathologic cancer detection - CNN classification project

This project uses Convolutional Neural Networks (CNN) to classify histopathologic images of tissue samples to detect the presence of cancer. The task is binary classification, predicting whether the center of a given image contains cancerous tissue. This project is an overdue participation in an old Kaggle competition.

Project Overview

Data Preparation: The dataset consists of images and their labels (cancer/no cancer). The data was preprocessed by resizing, normalizing, and augmenting images.

Model Architecture:
Model 1: A basic CNN with 3 convolutional layers followed by batch normalization, max pooling, and dropout for regularization.
Model 2: A similar architecture but with a custom training loop for better control over the training process.
Model 3 & 4: Enhanced architectures with deeper layers and dropout for further regularization, aimed at improving validation accuracy.

Key Steps:

Training: The models were trained using the Adam optimizer and binary crossentropy loss function, with various learning rates and dropout values.
Evaluation: Accuracy and loss metrics were used to evaluate the model performance on the validation set.

Results:
The models were compared based on validation accuracy and generalization performance using Kaggle scores.

Conclusion:
Deeper architectures and regularization strategies like dropout improved performance, but overfitting was observed in certain cases. Further tuning of hyperparameters and data augmentation could improve results.
