Dimensionality Reduction Techniques on MNIST Data
In this project, I have explored various techniques for dimensionality reduction using the MNIST number classification dataset. The MNIST dataset consists of images of handwritten digits, each of which is represented as a 28x28 pixel grid, resulting in 784 features per image.

Objective
The primary objective of this project was to apply different dimensionality reduction techniques to the high-dimensional MNIST dataset and visualize the results on a 2-dimensional graph. This not only helps in understanding the structure of the data but also in identifying patterns and clusters that are not easily discernible in higher dimensions.

Dataset
The MNIST dataset is a well-known dataset in the field of machine learning and computer vision. It contains 60,000 training images and 10,000 testing images of handwritten digits from 0 to 9, each normalized and centered in a fixed-size image of 28x28 pixels.

Techniques Explored
Several dimensionality reduction techniques were explored and applied to the MNIST data, including:

Principal Component Analysis (PCA):

PCA was used to reduce the dimensionality of the dataset by transforming it into a new set of variables (principal components) that are orthogonal and capture the maximum variance in the data.
t-Distributed Stochastic Neighbor Embedding (t-SNE):

t-SNE is a non-linear technique that is particularly effective for visualizing high-dimensional data in two or three dimensions. It works by converting similarities between data points to joint probabilities and minimizing the Kullback-Leibler divergence between the joint probabilities of the low-dimensional embedding and the high-dimensional data.
