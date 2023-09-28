# Non-Negative-Matrix-Factorization
Non-negative matrix factorization (NMF) is a technique to decompose a matrix of non-negative values into two smaller matrices, also with non-negative values. It can be used for dimensionality reduction, feature extraction, clustering, and other applications. This GitHub repository contains the implementation of NMF from scratch, using various optimization algorithms such as gradient descent, multiplicative update, and alternating least squares. The code is written in Python and uses NumPy for matrix operations. The repository also includes some examples of applying NMF to image and text data, as well as a comparison of the performance and accuracy of different algorithms. If you are interested in learning more about NMF and how to implement it, this repository is for you.

In this repository we look at a simple application of NMF to find out facial features and then reconstruct those face images using our updated Feature and Weight matrices. 

# Links
- [The Why and How of Non negative Matrix Factorization](https://arxiv.org/pdf/1401.5226.pdf?authuser=0)
- [A Deep Non-negative Matrix Factorization Model for Big Data Representation Learning](https://drive.google.com/file/d/11NR_KxLbHXmV9uEHRJI3ERGu7e5VXGCd/view)
- [A Deep Non-Negative Matrix Factorization Neural Network](https://www1.cmc.edu/pages/faculty/BHunter/papers/deep-negative-matrix.pdf?authuser=0)
- [Learning the parts of objects by non-negative matrix factorization](http://www.cs.columbia.edu/~blei/fogm/2020F/readings/LeeSeung1999.pdf?authuser=0)
- [Deep NMF Topic Modelling](https://arxiv.org/pdf/2102.12998.pdf?authuser=0)

# Dataset
The [Olivetti faces dataset](https://scikit-learn.org/0.19/datasets/olivetti_faces.html) is a collection of 400 grayscale images of 40 different human faces. The images were taken between April 1992 and April 1994 at AT&T Laboratories Cambridge1. The dataset was used for face recognition research and is available from scikit-learn, a Python library for machine learning2.

The images have a resolution of 64x64 pixels and are normalized to have the same lighting, background, and pose. The faces show different expressions, such as smiling or not smiling, and some have glasses or no glasses. The dataset has a label for each image, indicating the identity of the person in the range of 0 to 392.

The Olivetti faces dataset is a classic benchmark for face recognition algorithms and can be used for unsupervised or semi-supervised learning tasks. Some examples of using the dataset are online learning of a dictionary of parts of faces3, pixel importances with a parallel forest of trees4, face completion5, and face clustering6.
