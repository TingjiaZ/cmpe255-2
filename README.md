# cmpe255-2
Write a colab to demonstrate various dimensionality reduction techniques

Train.csv:
https://drive.google.com/file/d/1Q9JzJvHis9wBT6OxMODymaLv2nbKR7jB/view?usp=sharing

PCA - If the number of variables is large, it becomes hard to interpret the principal components. PCA is most suitable when variables have a linear relationship among them. Also, PCA is susceptible to big outliers.

SVD is a matrix factorization method which expresses a matrix as a linear combination of rank 1 matrices. SVD is more stable than PCA and it doesn't require a positive definite matrix.

For t-SNE to be meaningful we have to choose right value of perplexity. Perplexity balances the local and global aspects of the dataset. A Very high value will lead to the merging of clusters into a single big cluster and low will produce many close small clusters which will be meaningless

LLE is sensitive to outliers and noise. Datasets have a varying density and it is not always possible to have a smooth manifold. In these cases, LLE gives a poor result.

Isomap performs poorly when manifold is not well sampled and contains holes.
