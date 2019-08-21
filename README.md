# 3253_group

We use Machine Learning to help detect Diabetic Retinopathy from eye images.
The dataset is from: https://www.kaggle.com/c/aptos2019-blindness-detection/data

This is the final Project for SCS3253 (University of Toronto).

## Method
Using Keras API for TensorFlow

1. Use **ImageDateGenerator** to process the image data (image augmentation and train/test split)
2. Train with **Convolutional Neural Network** : 3 Conv2D layers each followed by MaxPooling2D layers and 2 Dense layers
3. Use Dropout, Learning Rate adjustment and Early Stopping to reduce overfitting

## Results
With **entropy set to 5**: loss: 0.8137 - accuracy: 0.7128 - val_loss: 0.8607 - val_accuracy: 0.6973
