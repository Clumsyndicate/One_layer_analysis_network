# One_layer_analysis_network

## Research info
This is a crude implementation of a one-layer network that is used in my Pioneer research project to study the effects of over-paramterization on the ability of the optimization function to find the global minima of the loss function.

Specifically, I studied the theoretical results of Du & Lee paper (https://arxiv.org/abs/1803.01206). I found some interesting results and revealed that their paper's results are quite limited in many ways, as neural networks behave well (can find global minima) in cases beyond their requirements, and their requirements are quite limiting. I also explored the similar circumstances with other activation functions.

## How to use this program
This program is an eager implementation of tensorflow. The different parameters can be adjusted. 
k -- number of hidden nodes
n -- number of training sets
d -- size of input
step -- training step

The latter three parameters could be adjusted directly, while there is a set of k paramters that is going to be looped over. In my paper, two different sets are used. 

The results would be outputed to a folder named with the chosen parameters. Every set of parameters would have a figure showing the loss function and an excel form to store all the data for further manipulation. 


## Credits

Check Pioneer Academics out: https://pioneeracademics.com/
Check out my paper。

