# Food_classifier

This repository allows for testing a transformer-based machine learning model designed for food recognition from images. It utilizes the Food-101 dataset along with the vit_b_16 model pretrained with neural network weights.

Subsequently, the neural network structure was modified to classify 101 different dishes, and transfer learning was applied to the heads of the ViT model. Training was carried out for 5 epochs on a 20% subset of the Food-101 dataset, resulting in an accuracy level of 55%.

The code was implemented using the Python language and the PyTorch library. Additionally, the program generates the necessary files for a Gradio interactive browser demo of the machine learning model.
