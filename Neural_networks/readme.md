Introduction to Neural Networks:
Neural networks refer to the representation we make using the brain. The human brain consists of
millions of neurons interconnected with each other which helps in processing information. Thus,
artificial neural networks are the computational model used to identify or recognize patterns, speech
recognition, text processing, etc. based on the principle of human brain neural networks.
Operation of Neural network:
Variables are entered as inputs (for example, an image that needs to be recognized), after passing the
input through the computational model, output i.e. the image isrecognized. Artificial neural networks
are organized in columns such that neurons of one column n is connected to neurons from column n-
1 and n+1.
Advantages of Neural network:
 Output obtained after the processing of inputs through a neural network model is not limited
to the input provided to the model.
 Loss of data is presented as the input data is not stored in an external database but its
networks.
 Model works for real-time events as networks can learn from similar examples and apply the
same when similar event occurs.
 System performance is not affected as multi-tasking is performed in parallel

Homework Outline: The goal of the assignment is to build a neural network model to add four-bit
numbers whose result is encoded as five-bit numbers.
Dataset description: The given dataset was downloaded from the link mentioned below:
https://drive.google.com/file/d/1MFx5BhjZswJepc9VOXdZp6fbwynCVZk8/view
The dataset has binary numbers x and y divided into 4 bits each. The result of the addition of the four
bits is encoded as five-bit binary numbers that include a +1 carry (bit). Using various combinations of
layers, activation, and loss functions, a neural network model is to be designed

Results:
The accuracy obtained for the sequential model built for the neural network is 86%. The maximum
accuracy obtained was using the combination of epoch value to be 1000 and batch size equal to 128
while using the optimizer value to be “adam” and the loss value to be “Categorical cross-entropy”.
Since the purpose of the model is to predict the output obtained after adding two four-bit binary
numbers X and Y, a simple neural network model called the sequential model was built which gave
the accuracy of 86%.
References:
[1] First Neural Network For Beginners Explained (with Code)
ArthurArnx-https://towardsdatascience.com/first-neural-network-for-beginners-explained-with-
code-4cfd37e06eaf
Dataset:
https://drive.google.com/file/d/1MFx5BhjZswJepc9VOXdZp6fbwynCVZk8/view
