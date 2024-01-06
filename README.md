# Image_Classification
Multi-Class Image Classification
<br>
Author- Jeevan Merkaji Somanna

# Introduction
The Data has 3736 images of different sizes and intensities for training and evaluating and 160 images for testing images. To enhance the training dataset, Data augmentations such as random cropping, flipping, rotating, and normalization were applied.

Transfer learning was employed using EfficientNet B4, and ConvNeXt Tiny from torch vision models trained on the ImageNet dataset, with the ConvNeXt Tiny model achieving a remarkable accuracy of 92% using pretrained weights.

# Requirements
See requirements.txt file

# Setup
Install PyTorch and other required Python libraries in a virtual environment with:

pip install -r requirements.txt
