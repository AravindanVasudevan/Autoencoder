# Deep Learning Model for Dimensionality Reduction

This project is an implementation of a deep learning model for dimensionality reduction using unsupervised learning techniques. The goal of the model is to take high-dimensional input images and transform them into lower-dimensional representations while preserving the most important information.

Model architecture is shown below:

<img width="337" alt="Screenshot 2023-05-10 002944" src="https://github.com/AravindanVasudevan/Autoencoder/assets/57245944/7ab04b9c-1094-42c7-80b3-349251ebae9d">

The model was implemented in Python using the PyTorch deep learning framework. It was trained on the Fashion-MNIST dataset, which consists of images of clothing items. During training, the model learned to reconstruct the input images using the bottleneck layer, which is a lower-dimensional representation of the input.

To visualize the effectiveness of the model, we used t-SNE, a popular technique for visualizing high-dimensional data in a lower-dimensional space. The bottleneck layer was used as input to t-SNE, and the resulting visualization showed that the model was able to cluster similar clothing items together.

The plot below shows the visulaization using t-SNE:

![Q4-tSNE](https://github.com/AravindanVasudevan/Autoencoder/assets/57245944/4f2366a4-4b4a-4469-ba5a-ce72cc188c87)

After reconstructing the input images, achieved an accuracy of 93% in classifying the images back into their original categories.
