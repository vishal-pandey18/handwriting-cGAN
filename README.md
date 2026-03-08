# Handwriting Digit Generator (cGAN)

This project uses a **Conditional GAN (cGAN)** built with PyTorch to generate handwritten digits (0–9), similar to the MNIST dataset.  

The notebook includes the **full workflow**: data loading, model definition, training, generating digits, and saving samples.  

## Features
- Conditional image generation for digits 0–9  
- Crisp digit visualization using nearest-neighbor upscaling  
- Modular code for training, inference, and saving generated images  
- Samples saved in `samples/` folder for easy reference  

## Installation
1. Clone the repository:

```bash
git clone <your-repo-url>

pip install -r requirements.txt

jupyter notebook Handwriting_Digit_Generator.ipynb
