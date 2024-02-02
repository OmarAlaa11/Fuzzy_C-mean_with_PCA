## PCA from Scratch
The main purposes of a principal component analysis are the analysis of data to identify patterns and finding patterns to reduce the dimensions of the dataset with minimal loss of information.
Dimensionality Reduction of the PCA helps us to visulaize the data in 2D,3D and improve Interpretability and also compresses the data.

First Calculate covariance matrix of the mean-centered data.
then Compute the Eigenvalues and Eigenvectors from scratch using power iteration method,
and Sort Eigenvalues in descending order.
then Select a subset from the rearranged Eigenvalue matrix and transformation of the data.


## Fuzzy C_mean Algorithm
Fuzzy logic principles can be used to cluster multidimensional data, assigning each point a membership in each cluster center from 0 to 100 percent. This can be very powerful compared to traditional hard-threshold clustering where every point is assigned a crisp,
exact label. This algorithm works by assigning membership to each data point corresponding to each cluster center on the basis of distance between the cluster center and the data point. More the data is near to the cluster center more is its membership towards the particular cluster center. Clearly, summation of membership of each data point should be equal to one.

It is an unsupervised clustering algorithm that permits us to build a fuzzy partition from data. The algorithm depends on a parameter m which corresponds to the degree of fuzziness of the solution. Large values of m will blur the classes and all elements tend to belong to all clusters. The solutions of the optimization problem depend on the parameter m. That is, different selections of m will typically lead to different partitions.

![Fuzzy _C-mean](https://github.com/OmarAlaa11/Fuzzy_C-mean_with_PCA/assets/142521907/0f97ac19-5a9f-4dd1-b0e3-3d6880b31ac2)

