# Deep Learning Projects

A collection of deep learning projects built with PyTorch and trained on Google Colab.

---

## Projects

### 1. MNIST Digit Classifier

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alicelmre2705/deep-learning-projects/blob/main/mnist_digit_classifier.ipynb)

A multi-layer perceptron (MLP) that classifies handwritten digits (0–9).

- **Dataset**: MNIST — 60k train / 10k test images (28×28 grayscale)
- **Architecture**: MLP with Dropout — 784 → 128 → 64 → 10
- **Result**: ~98% test accuracy

---

### 2. Alzheimer MRI Classifier

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alicelmre2705/deep-learning-projects/blob/main/alzheimer_mri_classifier.ipynb)

A CNN that classifies the severity of Alzheimer's disease from brain MRI scans.

- **Dataset**: [Augmented Alzheimer MRI Dataset](https://www.kaggle.com/datasets/uraninjo/augmented-alzheimer-mri-dataset) — 4 classes, 33k images
- **Classes**: Non Demented · Very Mild · Mild · Moderate
- **Architecture**: 3 conv blocks + Dense classifier with Dropout
- **Result**: ~94% validation accuracy

---

### 3. Cat Image Generator (DCGAN)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alicelmre2705/deep-learning-projects/blob/main/cat_image_generator.ipynb)

A Deep Convolutional GAN that generates 64×64 cat face images from random noise.

- **Dataset**: 15,747 cat face images (64×64 RGB)
- **Architecture**: DCGAN — Generator + Discriminator with BatchNorm
- **Result**: Recognizable cat faces after 20 epochs

---

## How to Run

Cliquez sur le badge **Open in Colab** du projet voulu, puis :

1. **Runtime → Change runtime type → T4 GPU**
2. **Runtime → Run all**

Les datasets se téléchargent automatiquement.

---

## Stack

- Python 3
- PyTorch & torchvision
- NumPy, Matplotlib, scikit-learn
- Google Colab (T4 GPU)
