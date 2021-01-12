# Network_Layer_Testing

The aim of this short project was to inspect and visualize the effect of variations in the number of layers of a DNN. To do this,
three separate DNNs were created. The first was created with two convolutional layers and three linear layers. The second network
was created with an additional convolutional and linear layer, and the third network with one less convolutional and linear layer
than the first network.

During training, data was recorded about the predictions of the network and compared to the labels for the dataset. A tally was 
kept to record the total number of correct predictions made during training. This was compared to the total number of images
passed through the network to track a 'total running accuracy'. This data was then visualized using tensorboard.


Predictions were also compared to the dataset labels and entered into a confusion matrix. The matrix is printed out at the end
of the script along with the total correct prediction for each network.

![alt text](https://github.com/tylerjzender/Network_Layer_Testing/blob/main/NetworkLayerTesting_ResultsAndMats.JPG?raw=true)

This project was an exercise for me to learn more about Pytorch and the development of neural networks. In addition, this 
project gave me an opportunity to both refresh and demonstrate my proficiency with python. 



