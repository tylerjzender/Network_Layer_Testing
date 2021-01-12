# Network Layer Testing Project

The aim of this short project was to inspect and visualize the effect of variations in the number of layers of a DNN. To do this,
three separate DNNs were created. The first was created with two convolutional layers and three linear layers. The second network
was created with an additional convolutional and linear layer, and the third network with one less convolutional and linear layer
than the first network.

During training, data was recorded about the predictions of the network and compared to the labels for the dataset. A tally was 
kept to record the total number of correct predictions made during training. This was compared to the total number of images
passed through the network to track a 'total running accuracy'. This data was then visualized using tensorboard.

![alt text](https://github.com/tylerjzender/Network_Layer_Testing/blob/main/NetworkLayerTesting_Tensorboard.JPG?raw=true)
Figure 1: Visualized data for each network's running total accuracy during training in tensorboard.

Predictions were also compared to the dataset labels and entered into a confusion matrix. The matrix is printed out at the end
of the script along with the total correct prediction for each network.

![alt text](https://github.com/tylerjzender/Network_Layer_Testing/blob/main/NetworkLayerTesting_ResultsAndMats.JPG?raw=true)
Figure 2: Produced data for each of the three networks including total number of correct predictions and confusion matrix.

Though this script includes only one trial for each of the three types of networks and though these networks are not necessarily
completely equivalent barring their difference in number of layers, the data points to the fact that the running accuracy for 
the network with only a single convolutional layer had the best statistical performance. This appears to occur primarily
because of the network learning faster. In the tensorboard visualization, the running accuracy improves faster in early
batches, presumably because there are fewer layers to adjust.

This project was an exercise for me to learn more about Pytorch and the development of neural networks. In addition, this 
project gave me an opportunity to both refresh and demonstrate my proficiency with python. 



