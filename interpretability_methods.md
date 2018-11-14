Methods of Interpretability for Deep Learning Models
===============================================================================

Machine learning algorithms, especially deep learning, have proved to provide great performances on various tasks like classification, object detection, segmentation, etc. but making decision based on these results comes with responsibilities and need to be supported with the evidences.

Here I try to organize most important ideas in the field of interpretable machine learning:

Decomposition-based methods
-------------------------------------------------------------------------------

- On the interpretation of weight vectors of linear models in multivariate neuroimaging \[[paper](http://dx.doi.org/10.1016/j.neuroimage.2013.10.067)\].
- Explaining NonLinear Classification Decisions with Deep Taylor Decomposition (2015) \[[paper](http://dx.doi.org/10.1016/j.patcog.2016.11.008)\].
- On pixel-wise explanations for non-linear classifier decisions by layer-wise relevance propagation (2015) \[[paper](http://dx.doi.org/10.1371/journal.pone.0130140)\]
- Towards Explaining Anomalies: A Deep Taylor Decomposition of One-Class Models (2018) \[[paper](https://arxiv.org/abs/1805.06230)\]

Gradient-based methods
-------------------------------------------------------------------------------

- **Class Activation Map (CAM)** : Learning Deep Features for Discriminative Localization’ \[[paper](http://dx.doi.org/10.1109/CVPR.2016.319)\].

- **Grad-CAM**: Selvaraju, R. R. et al.(2017) ‘Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization’ \[[paper](http://dx.doi.org/10.1109/ICCV.2017.74)\].

Representation Visualization and Quantification
-------------------------------------------------------------------------------

- **Network Dissection** is a method for quantifying interpretability of individual units in a deep CNN. 
It works by measuring the alignment between unit response and a set of concepts drawn from a broad and dense segmentation data set called Broden.
    \[[original paper](http://netdissect.csail.mit.edu/final-network-dissection.pdf),
    [extended paper](https://arxiv.org/pdf/1711.05611),
    [presentation](https://www.youtube.com/watch?v=Xy6RcjXMa2c)\]

- Visualizing and Understanding Convolutional Networks (2014) \[[paper](http://dx.doi.org/10.1007/978-3-319-10590-1_53)\]

- Striving for Simplicity: The All Convolutional Net (2014) \[[paper](https://arxiv.org/abs/1412.6806)\].

Developing Interpretable Models
-------------------------------------------------------------------------------