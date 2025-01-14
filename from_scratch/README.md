# What is in this directory
Here you will find codes in pure Python, where certain algorithms are coded from scratch. Below, you will a brief intro to each script in this directory.
## [Understanding SGD.py](https://github.com/MLDawn/MLDawn-Projects/blob/main/from_scratch/Understanding%20SGD.py)
This script creates a hypothetical loss function for the outputs of a simple model that has only 1 learnable parameter, w_0. Then the scripts shows you a 3D and 2D visualizations of the loss surface. Next, for a given initial value of our learable parameter, w_0, the gradient vectors are computed on multiple loss surfaces given each each input data. This shows you how the loss surface can change given the input data! Stochastic Gradient Descent (SGD) is then used to tune the value of w_0, and find the global minimum of the loss surface. The generated animation in the end, can make this exciting journey even more interesting.

![Screenshot](https://github.com/MLDawn/MLDawn-Projects/blob/main/from_scratch/images/sgd.png)
## [Understanding_relu.py](https://github.com/MLDawn/MLDawn-Projects/blob/main/from_scratch/Understanding_relu.py)
In this beautiful code, you will learn all that is to know about relu(z). You will visualize it, you will see its amazing flexibility and how it can bring us non-linearity. You will also learn how we can solve the non-differentiablity of relu(z) at z=0 using sub-gradients. Finally, you will see how you can develop a regressor using Pytorch and you will track the evolution of all of the relu()'s in the neural network and how they end up fitting a HIGHLY non-linear curve. Absolutely beautiful!
![Screenshot](https://github.com/MLDawn/MLDawn-Projects/blob/main/from_scratch/images/relu-training.png)
