# Normalizing Flows and Invertible Neural Networks in Computer Vision

*An ECCV 2020 Half-Day Tutorial*

### Overview 

This half-day ECCV 2020 tutorial will cover Normalizing Flows and Invertible Neural Networks with a specific focus on applications in computer vision.

Normalizing flows (NFs) offer an answer to a long-standing question in computer vision: 
How can one define faithful probabilistic models for complex high-dimensional data like natural images?
NFs solve this problem by means of non-linear bijective mappings from simple distributions (e.g. multivariate normal) to the desired target distributions.
These mappings are implemented with invertible neural networks and thus have high expressive power and can be trained by gradient descent in the usual way.
Thanks to bijectivity, NFs can work forward and backward, serving as discriminative and generative models alike, and are especially suitable for inverse problems.
This tutorial will explain the theoretical underpinnings of NFs, show various practical implementation options, clarify their relationships with GANs, VAEs, and non-linear ICA.
Particular emphasis will be given to successful applications in the field of computer vision.


### Target Audience
The tutorial is intended to be introductory, i.e., aimed at people with basic backgrounds in ML/CV who are interested in applying these methods in related problems.


### Organizers
- **Carsten Rother** Professor, University of Heidelberg, Germany
- **Ullrich Köthe** Professor, University of Heidelberg, Germany
- **Marcus A. Brubaker** Assistant Professor, York University, Canada
