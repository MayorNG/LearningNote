Within a CNN we apply a 3x3 kernel with stride = 1 and padding = 1 to a 50x50 **greyscale image** to obtain an output image of size HxW. In order to produce a H x W output from the same input image, how many additional parameters (including biases) would a fully connected layer require than the aforementioned convolutional layer? Select the correct answer from the following options.

Given the following statements about Autoencoders. Check all True statements
	1. Autoencoders can generate unseen data effectively
	2. lf an autoencoder was applied to the MNIST dataset, each class would have single latent representation
	3. The encoder of an autoencoder can be used to train a classifcation network with limited training data
	4. We don't know what the distribution in the latent space produced by an autoencoder will look like for thetrainining set.
	5. Autoencoders can help with clustering.

Given the following statements relating to CNNs, check all true statements
	1. One reason why CNNs are much more effcient than MLPs for spatial data is because the gradient for each weight in the convolutional kernel only ever depends on one pixel in the image/feature map it is applied to, called the receptive feld.
	2. CNNs require a larger number of parameters compared to MLPs applied for the same task.
	3. CNNs can be made more memory-effcient by downsampling the feature maps.
	4. We can use Stochastic Gradient Descent to optimize both convolutional neural networks and fully connected networks.
	5. CNNs are more effcient than MLPs for inputs with a large number of features.

We apply N convolutional kernels of dimension HxWxC (H, W and C are the height, width and number of channels respectively) with stride = 1 and padding = 0 to a 11x11 colour image. This results in a 7 by 7 feature map with 10 channels. What are the correct values for N, H, W, and C?

10 5 5 3

Given the following statements about the bottleneck layer found in Autoencoders. Check all Truestatements:
	1. The bottleneck forces the autoencoder to learn fne-grained details specifc to individual images.
	2. The number of neurons in the botleneck layer and the length of the latent representation are the same in anautoencoder.
	3. We need a bottleneck layer to make sure the network doesn't learn the identity function.
	4. The bottleneck layer serves as a compressed representation of the input data. Therefore, the input shouldnever be larger then the the bottleneck.
	5. The bottleneck layer should be smaller than both the input and output layers.

Check all true statements about the backpropagation algorithm:
	1. The backpropagation algorithm iteratively updates the network's weights to minimize the loss function,facilitating model learning and improvement.
	2. The backpropagation algorithm is an effcient way to compute the gradient of the loss function.
	3. Unfortunately, the backpropagation algorithm has many hyperparameters that have to be tuned to allow foran effcient computation of gradients on a given batch and computation graph.
	4. The computed activation functions are propagated backward through the computation graph.
	5. The backpropagation algorithm frst computes the gradient and then propagates it through the network in aforward and backward pass.

$$
data = \left[ \begin{matrix}
3 & 5 \\
2 & 4 \\
5 & 7 \\
4 & 6 \\
6 & 8 \\
8 & 11 \\
1 & 3 \\
7 & 10 \\
9 & 13 \\
10 & 14
\end{matrix} \right] 

target = \left[ \begin{matrix}
9 \\ 6 \\ 12 \\ 10 \\ 14 \\ 19 \\ 5 \\ 17 \\ 22 \\ 24
\end{matrix} \right] 
$$

|     | C1  | C2  | C3  | C4  | C5  | C6  | C7  | C8  | C9  | C10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1   | 34  | 26  | 50  | 42  | 58  | 79  | 18  | 71  | 92  | 100 |
| 2   | 26  | 20  | 38  | 32  | 44  | 60  | 14  | 54  | 70  | 76  |
| 3   | 50  | 38  | 74  | 62  | 86  | 117 | 26  | 105 | 136 | 148 |
| 4   | 42  | 32  | 62  | 52  | 72  | 98  | 22  | 88  | 114 | 124 |
| 5   | 58  | 44  | 86  | 72  | 100 | 136 | 30  | 122 | 158 | 172 |
| 6   | 79  | 60  | 117 | 98  | 136 | 185 | 41  | 166 | 215 | 234 |
| 7   | 18  | 14  | 26  | 22  | 30  | 41  | 10  | 37  | 48  | 52  |
| 8   | 71  | 54  | 105 | 88  | 122 | 166 | 37  | 149 | 193 | 210 |
| 9   | 92  | 70  | 136 | 114 | 158 | 215 | 48  | 193 | 250 | 272 |
| 10  | 100 | 76  | 148 | 124 | 172 | 234 | 52  | 210 | 272 | 296 |

|     | B1        | B2        |
| --- | --------- | --------- |
| 1   | 785/1921  | -548/1921 |
| 2   | -548/1921 | 385/1921  |

|     | C1   |
| --- | ---- |
| 1   | 937  |
| 2   | 1341 |


|C1|
|---|
|1|-1213/1921|
|2|1064/1921|
|3|-4/1921|
|4|352/1921|
|5|-360/1921|
|6|-184/1921|
|7|-501/1921|
|8|172/1921|
|9|348/1921|
|10|-8/1921|