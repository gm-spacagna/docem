# Document Embedding (DocEm)
The repository contains the code and notebooks for the tutorials on:
1. How to extract embedding features from COCO pictures using the ResNext model developed by Facebook AI.
2. Visualizing the picture embedding vectors in a 3D space using PCA and t-SNE.
3. Find the nearest neighbors of each picture based on the cosine distance.
3. Reduce the embedding space dimensionality while preserving manifold structures using UMAP.
4. Find the optimal GMM clusters using the BIC elbow method and the Silhouette analysis.
5. Visualize the pictures closest to each centroid to identify the cluster topic.
6. Apply an adapted version of the p-SIF (partition averaging) algorithm in order to produce document embeddings from the bag-of-word model and the original picture embedding vectors.
7. Test the effectiveness of the novel proposed method against the baseline methods for document averaging (weighted averaging and TF-IDF).

## Overview of the p-SIF algorithm

Original paper: [P-SIF: Document Embeddings Using Partition Averaging, V. Gupta et al.](https://arxiv.org/abs/2005.09069)

Algorithm overview diagram:

![alt text](p-sif-overview.png?raw=true)

## Read more

Articles of the "Embed, Cluster, Average" series:
* [Extracting rich embedding features from COCO pictures using PyTorch and ResNeXt-WSL](https://datasciencevademecum.com/2020/12/02/extracting-rich-embedding-features-from-pictures-using-pytorch-and-resnext-wsl/)
* [https://datasciencevademecum.com/2021/01/02/manifold-clustering-in-the-embedding-space-using-umap-and-gmm/](https://datasciencevademecum.com/2021/01/02/manifold-clustering-in-the-embedding-space-using-umap-and-gmm/)
* A novel approach to Document Embedding using Partition Averaging on Bag of Words (soon to be published)

## Experiment yourself

You can view and execute the development notebook in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nQK1YhvsyxOgYhqj5qA9zRYx9XHLGbnv#scrollTo=UTlfKj9WXqq7)
