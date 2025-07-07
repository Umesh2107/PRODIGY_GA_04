# 🧠 Image-to-Image Translation with Pix2Pix (cGAN)

This project implements an image-to-image translation model using a **Conditional Generative Adversarial Network (cGAN)** called **Pix2Pix**. The model is trained on the [Facades dataset](https://www.tensorflow.org/datasets/catalog/cycle_gan#cycle_ganfan), which maps building edge sketches to photo-realistic buildings.

---

## ✨ Features

- ✅ Uses TensorFlow 2.x and TensorFlow Datasets (TFDS)
- ✅ Prepares and normalizes paired image data
- ✅ Implements Pix2Pix Generator (U-Net) and Discriminator (PatchGAN)
- ✅ Trains the model end-to-end
- ✅ Visualizes predictions after training
- ✅ Downloads generated images locally from Colab

---

## 📁 Dataset

- **Name:** `cycle_gan/facades`
- **Type:** Paired image dataset
- **Source:** TensorFlow Datasets
- **Structure:**
  - `trainA`: input (edges)
  - `trainB`: target (photos)

---

## 🛠️ Installation

No setup needed in Colab.

If running locally:

```bash
pip install tensorflow tensorflow-datasets matplotlib pillow
