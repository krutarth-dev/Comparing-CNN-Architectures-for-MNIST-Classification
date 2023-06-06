# Comparing-CNN-Architectures-for-MNIST-Classification

In this task, we implemented three different CNN architectures using the TensorFlow library for the MNIST dataset. The goal was to create models with fewer than 8000 parameters and achieve a minimum accuracy of 96%.

First, we imported the necessary libraries and loaded the MNIST dataset. Then, we preprocessed the data by normalizing the pixel values and converting the labels to categorical format.

Next, we defined three CNN architectures with increasing complexity:

1. Architecture 1: This architecture consisted of a single convolutional layer with 32 filters, followed by max pooling, flattening, and two fully connected layers. The model was compiled with Adam optimizer and trained for 10 epochs.

2. Architecture 2: This architecture had two convolutional layers with 16 and 32 filters, respectively, followed by max pooling, flattening, and two fully connected layers. The model was compiled and trained similar to Architecture 1.

3. Architecture 3: This architecture added an additional convolutional layer with 8 filters to Architecture 2. All other layers remained the same. The model was compiled and trained similar to the previous architectures.

After training each model, we evaluated their performance on the test dataset and calculated their accuracy. Finally, we created a comparison table summarizing the accuracy achieved by each architecture.

This task allowed us to explore different CNN architectures and evaluate their performance on the MNIST dataset. By setting the parameter limit and accuracy threshold, we ensured that the models were efficient and achieved satisfactory results.
