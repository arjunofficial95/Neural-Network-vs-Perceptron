In this part, you apply a 3-layer Neural Network on a synthetically generated data to compare its performance with Perceptron. Here, we are looking for your explanation about the differences between perceptron and NN that leads to different results.

1. Load Task2B_train.csv and Task2B_test.csv sets, plot the training data with classes are marked with different colors.

2. Train two perceptron models on the loaded training data by setting the learning rates η to .01 and .09 respectively. Calculate the test errors of two models and find the best η and its corresponding model, then plot the test data while the points are colored with their estimated class labels using the best model that you have selected.

3. For each combination of K (i.e, number of units in the hidden layer) in {5, 10, 15, ..., 100} and μ (learning rate) in {0.01, 0.09}, run the 3-layer Neural Network and and record testing error for each of them (40 models will be developed, based on all possible combinations). Plot the error for μ 0.01 and 0.09 vs K (one line for μ 0.01 and another line for μ 0.09 in a plot).
