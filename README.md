# mnist_digit_recognizer

This repository currently contains two types of solutions that can classify a numeric value to a handwritten digit.

On my first attempt to classify each handwritten number in the dataset, I used a simple K-Nearest Neighbors classification algorithm.
Since the handwritten numbers represent values from 0 to 9, the KNN model assigns a class for each numeric value. By training the model using training data, the algorithm was able to create classes for each numeric value and assign data to the class that had the nearest neighbors. From this method I achieved an accuracy of 96.603% by comparing the model's predictions to the actual values.

I wanted my first attempt to be the benchmark, therefore, I was keen to improve my KNN algorithm to get the highest accuracy as possible. After various tests, I found the optimized value of k that increased the accuracy of the model to 96.728%. However, the difference between the accuracies of the two KNN models was minimal and not the result I desired. I knew that I had to abandon the KNN algorithm as resort to a neural network for more accurate results.

Using Keras, I created a simple neural network that managed to generate predictions with an accuracy of 99.078%.



