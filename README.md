# 🧠 Waste Classification Using Transfer Learning

This project focuses on building a deep learning-based image classifier that distinguishes between 9 types of waste using transfer learning. The motivation behind this project is to improve waste sorting efficiency by leveraging pre-trained convolutional neural networks on relatively small datasets.

## 🌟 What This Project Does

- Uses transfer learning with powerful pre-trained models like **ResNet50**, **EfficientNetB0**, and **VGG16**
- Classifies images of waste into 9 categories with high accuracy
- Applies **data augmentation** techniques (flip, rotate, crop, zoom, contrast, etc.) to boost model generalization
- Implements **fine-tuning** by freezing base model layers and training the top dense layers
- Tracks performance using **accuracy**, **precision**, **recall**, **F1-score**, and **AUC**

## 🔧 Technologies Used

- **Python**
- **TensorFlow** / **Keras**
- **OpenCV** for image preprocessing
- **Matplotlib / Seaborn** for performance visualization

## 📈 Model Training Highlights

- Trained for up to **100 epochs** with **early stopping** based on validation loss
- Used **ReLU activations**, **L2 regularization**, **Batch Normalization**, and **Dropout**
- Validation set created using an **80/20 split** of the dataset
- Tracked metrics across multiple models to identify the best performer



