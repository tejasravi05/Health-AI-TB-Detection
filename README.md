# 🩻 Tuberculosis Detection from Chest X-Rays using CNN

This project uses a Convolutional Neural Network (CNN) model to classify chest X-ray images as either **Tuberculosis-positive** or **Normal**. The model is trained on a publicly available dataset and developed using Google Colab with Keras and TensorFlow.

---

## 🗂️ Dataset

- The dataset used consists of chest X-ray images divided into **TB-infected** and **Normal** categories.
- Source: [Google Drive Dataset Link](https://drive.google.com/drive/folders/1xxBjvdWqKW5B5VRcnk3mecmIZvtAFr7X?usp=sharing)

> ⚠️ The dataset is not included in this repository due to size limitations. Please download it manually from the link above and upload it to your Google Drive.

---

## 🧠 Model Details

- **Architecture:** Sequential CNN with:
  - 4 Convolutional layers (With L2 Regularization)
  - MaxPooling layers
  - Flatten + Dense layers
  - Output layer with sigmoid activation
  - Dropout layer
- **Loss Function:** Binary Crossentropy
- **Optimizer:** Adam
- **Input Size:** 224x224 (resized from original)
- **Epochs:** 20 (adjustable)
- **Batch Size:** 64
---

## 🛠️ Libraries Used

- TensorFlow & Keras
- NumPy
- OpenCV (cv2)
- Matplotlib
- Google Colab (Drive access)
- Sklearn
---

## 🚀 How to Run the Project

1. Download the dataset from the link above.
2. Upload it to your **Google Drive**.
3. Open the notebook in **Google Colab**.
4. Mount your Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
5. Update the path to the dataset if needed.
6. Run all cells in order to preprocess, train, and evaluate the model.

