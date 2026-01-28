# Lanzaderas-Edwin_LW1-Image-Classification

Questions: (February 8, 2026)
1. What is the Fashion MNIST dataset?
The Fashion MNIST dataset consists of 28x28 grayscale photos of many types of clothes, including shirts, pants, shoes, and purses. It is frequently used in image classification applications in place of the original MNIST digit dataset and comprises 60,000 images for training and 10,000 images for testing.

2. Why do we normalize image pixel values before training?
The normalization of pixel values from 0–255 to 0–1 facilitates faster and more stable training. The neural network learns more efficiently as a result of this procedure, which also enhances optimization performance.

3. List the layers used in the neural network and their functions.
The image is transformed into a one-dimensional vector via the Flatten layer. Important features are extracted from the data by dense layers with Relu activation, and prediction scores for the ten clothing classes are produced by the final dense layer.

4. What does an epoch mean in model training?
One complete transit of the training data through the neural network is called an epoch. The model can learn better by using more epochs, but overfitting may result from using too many.

5. Compare the predicted label and actual label for the first test image.
For the first test image, the predicted label was the same as the actual label, which means the model successfully classified the image.

6. What could be done to improve the model’s accuracy?
You can improve the model’s accuracy by adding more hidden layers, using more or fewer neurons, training for more epochs, or using a more advanced model design
