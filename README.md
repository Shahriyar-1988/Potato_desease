
# Potato Disease Classification with CNN

This is a portfolio project to showcase my abilities to work with unstructured data (i.e., images) and convolutional neural networks (CNNs). The goal of this project is to classify images of potato leaves into healthy or diseased categories using a deep learning model built with TensorFlow and Keras.

## 🧠 Project Overview

This notebook demonstrates a complete deep learning pipeline including:
- Loading and preprocessing image data from Google Drive
- Applying data augmentation layer  to improve generalization
- Using a pre-trained **ResNet** model for transfer learning
- Building and training a CNN classifier
- Evaluating model performance and visualizing results

## 📁 Dataset

The dataset is expected to be structured inside Google Drive as follows:

```
Potato_Disease_Dataset/
├── Healthy/
│   ├── image1.jpg
│   └── ...
├── Early_Blight/
│   ├── image1.jpg
│   └── ...
├── Late_Blight/
│   ├── image1.jpg
│   └── ...
```

Make sure the dataset is accessible through a mounted Google Drive session in Colab.

## 🧰 Technologies Used

- Python
- TensorFlow & Keras
- ResNet50 (pre-trained model)
- Google Colab
- Google Drive
- Matplotlib

## 📈 Results

The model achieves strong accuracy on the validation set and is capable of distinguishing between multiple types of potato leaf conditions. Data augmentation helps the model generalize better to unseen data.

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Mount your Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
3. Ensure the dataset path in the code matches your Drive structure.
4. Execute all cells sequentially to train and evaluate the model.

## 📌 Future Improvements

- Hyperparameter tuning using Keras Tuner or manual search
- Improve visual reporting (confusion matrix, class-wise accuracy)
- Convert the trained model to TensorFlow Lite for mobile deployment

## 📬 Contact

Feel free to reach out for questions, suggestions, or collaboration opportunities.
