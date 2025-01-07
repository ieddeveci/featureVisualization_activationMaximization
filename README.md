# Feature Visualization via Activation Maximization of Deep Neural Networks

Feature visualization is a powerful technique for improving the interpretability of deep neural networks. Activation maximization is particularly popular for visualizing the learned features of a network unit. Through gradient ascent, this approach generates human-interpretable images that reveal what the neural network is effectively looking for in the input.

The code implements a pipeline for generating a visualization that highlights features associated with a specific ImageNet class using a Residual Network (ResNet50) and a Vision Transformer (ViT-B16) model. It incorporates image augmentations during optimization to improve generalization and robustness.

Example generated images for class index 852 (tennis ball):

![ResNet18_visualization_1000_withAugmentations](https://github.com/user-attachments/assets/6099ad4d-c0aa-485d-ae0f-1c738808d862)
![ResNet18_visualization_6000_withAugmentations](https://github.com/user-attachments/assets/91105482-5787-4839-89d6-4ade93c5bcd5)
![ResNet18_visualization_10000_withAugmentations](https://github.com/user-attachments/assets/692443c9-8305-4c02-a03f-17adf081cb67)


