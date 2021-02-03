# Dog-Visioner

## Quick Summary
This is the one of the courseworks from **Complete Machine Learning and Data Science by Daniel Bourke on Udemy**.

This project uses **transfer learning** to identify different breeds of dogs from dataset[2] with **mobilenet_v2_130_224**.

This notebook differs from the example given in the coursework but generally follows:
1. Download and preprocess data into Tensors
2. Choose a pre-trained deep learning model from TensorFlow Hub to fit the data.
3. Evaluating the model

I tried to construct this project from scratch myself after finishing following along the coursework and test out techniques learnt from reading TensorFlow Image classification tutorials.
In addition, I also tried to address the overfitting issues by comparing and ploting accuracies between the training and test set and add one extra layer of augmentation; and then trained on a bigger dataset.

After completing the coursework, it does provide an entry point into the deep learning horizon and I was able to explore more about different functions and applications.

## Reference
[1] https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/

[2] https://www.kaggle.com/c/dog-breed-identification/overview

