# Sketch-to-Real-Synthesizing-Images
Generating realistic images from hand-drawn sketches is a challenging task in computer
vision. This project introduces a Sketch-to-Image Autoencoder that utilizes Convolutional
Neural Networks (CNNs). The autoencoder architecture is built with an encoder-decoder
framework, which is trained using a dataset containing paired sketches and their
corresponding real images. The encoder network is trained to transform input sketches into
a latent space representation, whereas the decoder network recreates the original image
using this representation.
The model is trained through a dataset of hand-drawn sketches paired with associated real
images. The training process focuses on fine-tuning the model's parameters to minimize
any discrepancies between the created images and actual images. The model's performance
is assessed by utilizing metrics like Structural Similarity Index (SSIM). The proposed
approach has been proven to be highly effective in generating top-notch images from input
sketches, as shown by the experimental results. The trained model has a wide range of
applications, including Forensic Investigations, Digital Art and Design, Fashion Design,
etc.
