# Custom Conditional GAN on MNIST

This project implements a **Conditional Generative Adversarial Network (cGAN)** trained on the **MNIST dataset** of handwritten digits using **PyTorch Lightning**. Unlike standard GANs, a cGAN learns to generate images conditioned on class labels, allowing controlled generation of digits (0–9).

## 🚀 Features

- **Custom GAN architecture** built from scratch in PyTorch.
- **Conditional generation** – generate specific digits by providing labels.
- **PyTorch Lightning integration** for clean training loops and GPU support.
- **MNIST dataset preprocessing** with normalization for stable GAN training.
- **Visualization of results** – sample images generated during training.

## 📂 Project Structure

- `Custom_GAN_MNIST.ipynb` – main notebook containing the full implementation, training, and results.
- **Generator**: Accepts random noise + digit labels and outputs fake MNIST images.
- **Discriminator**: Learns to distinguish real MNIST digits from generated ones.

## 🛠️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/Custom-GAN-MNIST.git
cd Custom-GAN-MNIST
pip install -r requirements.txt
```

Or install dependencies directly inside Jupyter:

```python
!pip install pytorch-lightning torchvision matplotlib
```

## 📊 Training

The GAN is trained using the MNIST dataset:

```python
# Run notebook cells in Custom_GAN_MNIST.ipynb
```

Training will display loss curves and generate sample images as the model improves.

## 🎨 Results

After training, the generator can produce realistic handwritten digits for any given label. Example:

- Input: noise + label = "7"
- Output: generated digit that looks like a handwritten **7**.


