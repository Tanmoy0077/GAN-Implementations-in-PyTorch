# GAN Implementations in PyTorch

## Description

This repository contains PyTorch implementations of three Generative Adversarial Networks (GAN) architectures:

1. **CycleGAN**: Cycle-Consistent Adversarial Networks for unpaired image-to-image translation.
2. **WGAN**: Wasserstein GAN for improved training stability and more interpretable loss metric.
3. **VanillaGAN**: The original GAN architecture for generating data from random noise.

### CycleGAN

CycleGAN allows for image-to-image translation tasks where paired examples are not available. The key idea is to train two generator-discriminator pairs to perform mutual mappings between two domains.

### WGAN

Wasserstein GAN improves the training of GANs by using the Earth Mover's distance (Wasserstein distance) as a loss metric. This approach helps to address issues of mode collapse and provides more meaningful loss values.

### VanillaGAN

The VanillaGAN is the original formulation of GANs, where a generator network learns to produce data resembling the training data, and a discriminator network learns to distinguish between real and generated data.

## Dataset

The datasets used for training these GANs can be found at the following links:

- [CycleGAN Dataset](https://drive.google.com/file/d/1M00Ad2e-Iu1eU9GMEO8Kc0o64W2ZBhra/view?usp=sharing)

Rest are mentioned in the jupyter notebooks

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- The CycleGAN implementation is based on the original paper by [Zhu et al.](https://arxiv.org/abs/1703.10593).
- The WGAN implementation follows the guidelines from the [Arjovsky et al. paper](https://arxiv.org/abs/1701.07875).
- The VanillaGAN implementation is based on the seminal work by [Goodfellow et al.](https://arxiv.org/abs/1406.2661).

---

For further information and questions, feel free to open an issue or contact the repository maintainers.