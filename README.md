Interpretable Machine Learning
===============================================================================

Machine learning algorithms, especially deep learning, have proved to provide great performances on various tasks like classification, object detection, segmentation, etc. but making decision based on these results comes with responsibilities and need to be supported with the evidences.
Medicine particularly is an area that decisions comes with a huge responsibility, so for machine learning to be useful in clinics and to aid clinicians, it requires to provide evidences for its output and in other words be *interpretable*.

Here I try to organize most important ideas in the field of interpretable machine learning and explore its applications in medicince.

[Methods of Interpretability for Deep Learning Models](./interpretability_methods.md)
-------------------------------------------------------------------------------

- [Decomposition-based methods](./interpretability_methods.md#decomposition-based-methods)\
  These methods try to decompose the value of target into contribution of different nodes in the network.

- [Gradient-based methods](./interpretability_methods.md#decomposition-based-methods)\
  These methods try to find how a change in each of the nodes affect the target.

- [Representation Visualization and Quantification](./interpretability_methods.md#representation-visualization-and-quantification)\
   These methods try to make sense of inner layers and understand what they are representing.

[Applications of Interpretability in Medicine](./interpretability_in_medicine.md)
-------------------------------------------------------------------------------

- [Intracranial Hemorrhage](./interpretability_in_medicine.md#intracranial-hemorrhage)
- [Stroke](./interpretability_in_medicine.md#stroke)
- [ECG](./interpretability_in_medicine.md#eeg)
- [Electronic Health Records](./interpretability_in_medicine.md)
- [Radiology Reports](./interpretability_in_medicine.md)

[Applications of Interpretability in Smart Cities](./interpretability_applications.md)
-------------------------------------------------------------------------------

- [Self Driving Cars](./interpretability_applications.md#self-driving-cars)

[Tools of Interpretability in Practice](./interpretability_methods.md)
-------------------------------------------------------------------------------

- [What-If](https://pair-code.github.io/what-if-tool/)
- [Facet](https://pair-code.github.io/facets/)
- [SmoothGrad](https://github.com/pair-code/saliency)
- [Embedding Projector](http://projector.tensorflow.org)
- [Play Ground](http://playground.tensorflow.org/)
