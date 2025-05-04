# Variational Autoencoder on FashionMNIST
This project implements a basic Variational Autoencoder (VAE) to reconstruct and sample FashionMNIST images, based on the original concept from [Kingma & Welling (2013)](https://arxiv.org/abs/1312.6114).
The goal was primarily to experiment with VAEs and evaluate reconstruction quality and sample realism using the FID score.

**⚠️ Note:** This implementation is a minimal version and not optimized. It can be improved by tuning hyperparameters (e.g. latent_dim, β) or using more advanced variants such as:
- β-VAE (Higgins et al.)
- VQ-VAE (van den Oord et al.)
- VAE-GAN
- Diffusion-based decoders
