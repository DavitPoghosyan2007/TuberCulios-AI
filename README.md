# 🫁 Tuberculosis Detection using CNN

## 📌 About the Project

This project uses a Convolutional Neural Network (CNN) to classify chest X-ray images into two categories:

- **Normal** — lungs without tuberculosis
- **Tuberculosis** — images labeled as tuberculosis

The model is built with TensorFlow/Keras and uses image preprocessing techniques to prepare X-ray images for classification.

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn

## 🧠 Model Architecture

The CNN model includes:

- Convolutional layers for feature extraction
- MaxPooling layers for dimensionality reduction
- Fully connected Dense layers
- Softmax output layer for binary classification

### Model Configuration

- **Input image size:** 300 × 300 pixels
- **Input channels:** 3 (RGB)
- **Optimizer:** Adam
- **Learning rate:** 0.001
- **Loss function:** Categorical Crossentropy
- **Epochs:** 10

## 📂 Dataset Structure

The dataset is expected to have the following structure:

```text
Bardxndir/
├── Normal/
│   ├── image1.jpeg
│   └── image2.jpeg
└── Tuberculosis/
    ├── image1.jpeg
    └── image2.jpeg
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/DavitPoghosyan2007/tuberculosis-detection.git
cd tuberculosis-detection
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn opencv-python scikit-learn tensorflow
```

## 🚀 How to Run

1. Download and organize the dataset into the `Bardxndir` folder.
2. Open `Untitled1.ipynb` in Jupyter Notebook.
3. Run the notebook cells in order.
4. Train the CNN model.
5. Test the model using a chest X-ray image.

## 🔍 Prediction

The trained model predicts one of two classes:

- `0` — Tuberculosis
- `1` — Normal

## 🎯 Project Goal

The goal of this project is to explore how deep learning and computer vision can be applied to medical image classification.

## ⚠️ Disclaimer

This project is for educational and research purposes only. It is not intended to replace professional medical diagnosis.

## 👨‍💻 Author

**Davit Poghosyan**

GitHub: [@DavitPoghosyan2007](https://github.com/DavitPoghosyan2007)
