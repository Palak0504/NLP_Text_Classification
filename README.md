# Transfer Learning with Pre-trained VGG16

This repository contains a Google Colab implementation of **transfer learning** using a **pre-trained VGG16** model on the **UEH-VDR (Vietnamese Dish Recognition)** dataset.  
It demonstrates how to adapt powerful existing models for new classification tasks quickly and effectively.

---

## ✨ Features

- **Pre-trained VGG16**: Loaded from PyTorch's torchvision models.
- **Fine-tuning**: Modified the classifier to match the number of classes in the new dataset.
- **Data Augmentation**: Random transformations applied to improve model robustness.
- **GPU Acceleration**: Utilized Google Colab GPU for faster training.
- **Visualization**: Displayed model predictions on sample test images.

---

## 📂 Dataset

The dataset used:

**UEH-VDR (Vietnamese Dish Recognition Dataset)**  
[Kaggle Link](https://www.kaggle.com/datasets/truthtaicom/uehvdr-dataset)

Please download the dataset, upload it to your Google Drive, and link it in the notebook.

---

## 🛠 Requirements

The notebook is optimized for **Google Colab**.  
No installation required if using Colab.

If running locally, install:

```bash
pip install torch torchvision matplotlib numpy
