# Feature Visualization via Activation Maximization
Feature Visualization of Deep Neural Networks, Term Project, MMI727

feature visualization is a powerful technique for improving the interpretability of deep neural networks. Activation maximization is particularly popular for visualizing the learned features of a network unit. Through gradient ascent, this approach generates human-interpretable images that reveal what the neural network is effectively looking for in the input.

The code implements a pipeline for generating a visualization that highlights features associated with a specific ImageNet class using a Residual Network (ResNet50) and Vision Transformer (ViT-B16) model. It incorporates image augmentations during optimization to improve generalization and robustness.
