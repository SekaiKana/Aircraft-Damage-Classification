# Aircraft-Damage-Classification

This project demonstrates an **Image Classification and Captioning pipeline** using deep learning. It leverages **VGG16** from Keras/TensorFlow for feature extraction and applies custom layers for training and evaluation.

---

## 🚀 Features
- Pretrained **VGG16** backbone for image classification.
- Custom classification layers with **Dense, Dropout, and Flatten**.
- **ImageDataGenerator** for training/validation image augmentation.
- Handles dataset preprocessing, extraction, and organization.
- Visualization of training metrics using **Matplotlib**.

---

## ⚙️ Installation
Clone the repository and install the required dependencies:

bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt

## 📊 Training Notes

During the training process, the validation accuracy score remained constant.
This was traced back to corrupt images in the dataset, which prevented proper learning on the validation split.
Cleaning or filtering these corrupt images is required for improved validation performance.

## 📈 Example Outputs

- Training and validation accuracy/loss plots.
- Predicted labels on sample images.
- Captioning results with pretrained models (if implemented).

## 🛠 Requirements
See requirements.txt
