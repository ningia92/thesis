# Computer science thesis at University of Bari (2023)
## Generative deep learning models for cybersecurity

The work object of my thesis falls within the research area of ​​Machine Learning applied to cybersecurity. Specifically, neural models are adopted for the generation and classification of malware.

The thesis addresses the problem of the low accuracy of a classifier in distinguishing malware images that differ from those present in the training set. The causes of this problem are due to the low quantity or variety of examples used to train the classifier.

The proposed solution, to improve the performance of the classifier, consists in the use of a generative Deep Learning model, called GAN (Generative Adversarial Networks), to generate synthetic images that will increase the size and diversity of the training set (data augmentation). Specifically, a variant of GAN, called WCGAN-GP (Wassertein Conditional Generative Adversarial Networks with Gradient Penalty), is used.

For this purpose, a dataset of images representing malware was taken and used to train the GAN, with which new examples were then generated. The neural network ResNet (Residual Network) was used to perform the classification.

The results revealed that, through the use of data augmentation, with artificially generated data, there can be a clear improvement in the performance of the classifier.
