Methods of Interpretability for Deep Learning Models
===============================================================================

Machine learning algorithms, especially deep learning, have proved to provide great performances on various tasks like classification, object detection, segmentation, etc. but making decision based on these results comes with responsibilities and need to be supported with the evidences.

Here I try to organize most important ideas in the field of interpretable machine learning:

Decomposition-based Methods
-------------------------------------------------------------------------------

- On the interpretation of weight vectors of linear models in multivariate neuroimaging. \[[paper](http://dx.doi.org/10.1016/j.neuroimage.2013.10.067)]
- Explaining NonLinear Classification Decisions with Deep Taylor Decomposition (2015). \[[paper](http://dx.doi.org/10.1016/j.patcog.2016.11.008)]
- On pixel-wise explanations for non-linear classifier decisions by layer-wise relevance propagation (2015). \[[paper](http://dx.doi.org/10.1371/journal.pone.0130140)]
- Towards Explaining Anomalies: A Deep Taylor Decomposition of One-Class Models (2018). \[[paper](https://arxiv.org/abs/1805.06230)]

Gradient-based Methods
-------------------------------------------------------------------------------

- **Class Activation Map (CAM)** : Learning Deep Features for Discriminative Localization. \[[paper](http://dx.doi.org/10.1109/CVPR.2016.319)]
- **Grad-CAM**: Visual Explanations from Deep Networks via Gradient-Based Localization. \[[paper](http://dx.doi.org/10.1109/ICCV.2017.74)]
- **Grad-CAM++**: Building on Grad-CAM, it provides better visual explanations of CNN model predictions, in terms of better object localization as well as explaining occurrences of multiple object instances in a single image. \[[paper](https://arxiv.org/abs/1710.11063)]
- **SmoothGrad**: removing noise by adding noise \[[paper](https://arxiv.org/abs/1706.03825)] \[[code](https://github.com/pair-code/saliency)] \[[more descriptions](https://pair-code.github.io/saliency/)]

- **Integrated Gradients**: Axiomatic Attribution for Deep Networks. It uses to  two fundamental axioms *Sensitivity* and *Implementation Invariance* to guide the design of a new attribution method. \[[paper](https://arxiv.org/abs/1703.01365)] \[[code](https://github.com/ankurtaly/Integrated-Gradients)]

- Vanilla Gradients (paper, paper)

Representation Visualization and Quantification
-------------------------------------------------------------------------------

- **Network Dissection**: It quantifies interpretability of individual units in a deep CNN. It works by measuring the alignment between unit response and a set of concepts drawn from a broad and dense segmentation data set called Broden. \[[original paper](http://netdissect.csail.mit.edu/final-network-dissection.pdf), [extended paper](https://arxiv.org/pdf/1711.05611), [presentation](https://www.youtube.com/watch?v=Xy6RcjXMa2c)]

- Visualizing and Understanding Convolutional Networks (2014). \[[paper](http://dx.doi.org/10.1007/978-3-319-10590-1_53)]

- Striving for Simplicity: The All Convolutional Net (2014). \[[paper](https://arxiv.org/abs/1412.6806)]

- Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps (2013). \[[paper](https://arxiv.org/abs/1312.6034)]

Others
-----------

- Examples are not Enough, Learn to Criticize! Criticism for Interpretability. \[[paper](https://papers.nips.cc/paper/6300-examples-are-not-enough-learn-to-criticize-criticism-for-interpretability.pdf)]
- Explanation in Artificial Intelligence: Insights from the Social Sciences. \[[paper](https://arxiv.org/abs/1706.07269)]