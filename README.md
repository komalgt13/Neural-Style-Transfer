# Neural-Style-Transfer

## Overview 

<p>The problem at hand is to develop a <b>Neural Style Transfer (NST) model</b> capable of transforming ordinary photographs into artistic masterpieces by applying the stylistic features of renowned painters like Van Gogh, Picasso, or Monet. Neural Style Transfer is a deep learning technique that merges the content of one image with the artistic style of another, creating visually appealing and artistically coherent new visuals.
</p>

### Objectives

- Develop a Neural Style Transfer Model : Implement a deep learning model using convolutional neural networks (CNNs) to extract and transfer artistic styles from reference images (e.g., paintings) onto input images (e.g., photographs).

- Preserve Content Structure : Ensure that while applying the artistic style, the structure and details of the original content image remain largely unchanged. This involves balancing the style transfer process to retain the content's semantic information.

- Achieve Visual Appeal and Coherence : The primary goal is to create stylized images that are not only visually appealing but also maintain a coherent artistic style throughout the image.

- Implementation Options : Provide flexibility in how the model is showcased, such as creating a user-friendly web interface for image uploads and style selection, or integrating the model into existing artistic creation software tools.
<br>
<br>


### Usage 
- Store the name of the image and the style to be used at the simulation in the following variables 
  - initial_images = ["joker.jpg"] 
  - style_images = ["oilPainting.jpg"]
- Run the simulation

### Dependencies

- PyTorch : A deep learning framework for tensor computations and neural network training.
  - torch: Core PyTorch library.
  - torch.nn: Neural network module for building and training networks.
  - torch.optim: Optimization algorithms for gradient descent
  - torchvision: Provides datasets, transforms, and pre-trained models for computer vision tasks.

- Pillow (PIL): Python Imaging Library for image processing tasks. PIL.Image Module for opening, manipulating, and saving images.
  - Matplotlib : Plotting library for creating visualizations.
  - Python Standard Libraries:
    - os: Provides functions for interacting with the operating system, used for file and directory operations
    - copy: Used for creating deep copies of objects, essential for duplicating neural network models.

- Warnings: Python module for handling warnings.

### Installation Instructions:
To install these dependencies, you can use `pip`, Python's package installer:

```bash
pip install torch torchvision pillow matplotlib
```

Ensure that you have Python installed on your system. Using a virtual environment (`virtualenv`, `conda`, etc.) is recommended to manage dependencies and avoid conflicts with other projects.
  

