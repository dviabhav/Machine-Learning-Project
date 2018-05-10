# Machine-Learning-Project
Personal experiment on digit recognition 


Having started working on machine learning and neural netowrks, this is my attempt at experimenting with various neural net architectures. The neural net uses 5000 20x20 pixel images of digits to train and recognise hand-written nunmbers. This example is used as an introductory model to familiarise students with neural networks and backpropogation. Conventionally the network comprises of three layers, the input, output and one hidden layer.

Instead, I choose to have four layers, the first hidden layer comprises of 40 neurons divided into 10 subgroups. Each subgroup of 10 works with 100 pixels of the image (slicing the image in four pieces). Then, the response of all the 40 neurons from the second layer is forwarded to the second hidden layer comprising of 20 neurons, eventually going to a 10 neuron layer which is used as an output. The goal is to measure efficiency of this architecture comprising of, in total, 4450 parameters, to a simplere architecture of comparable number of parameters. 
