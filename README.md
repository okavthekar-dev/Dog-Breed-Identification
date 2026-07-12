# 🐶 Dog Vision - Dog Breed Identification

An end-to-end Deep Learning project that classifies images of dogs into **120 different breeds** using **Transfer Learning** with **TensorFlow** and **MobileNetV2**. This project demonstrates the complete machine learning workflow, from data preprocessing and model training to evaluation and Kaggle competition submission.

---

## 📌 Project Overview

The goal of this project is to accurately identify the breed of a dog from an input image. Instead of training a convolutional neural network (CNN) from scratch, a pre-trained **MobileNetV2** model is used as a feature extractor through **Transfer Learning**, resulting in faster training and high classification performance.

---

## 📂 Dataset

* **Dataset:** Kaggle Dog Breed Identification
* **Number of Classes:** 120 Dog Breeds
* **Training Images:** 10,222
* **Test Images:** 10,357

---

## 🚀 Features

* Image preprocessing and resizing
* One-hot encoded labels
* TensorFlow `tf.data` input pipeline
* Transfer Learning with MobileNetV2
* Model training using TensorFlow & Keras
* EarlyStopping, ModelCheckpoint, and TensorBoard callbacks
* Model evaluation
* Prediction on unseen test images
* Kaggle submission file generation

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* TensorFlow Hub
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab(GPU)

---

## 🧠 Model Architecture

* **Base Model:** MobileNetV2 (TensorFlow Hub)
* **Input Image Size:** 224 × 224 × 3
* **Output Layer:** Dense layer with 120 neurons (Softmax activation)
* **Loss Function:** Categorical Crossentropy
* **Optimizer:** Adam
* **Evaluation Metric:** Accuracy

---

## 📊 Workflow

1. Load and preprocess image data
2. Create TensorFlow data pipelines
3. Encode labels
4. Build the Transfer Learning model
5. Train the model with callbacks
6. Evaluate model performance
7. Predict dog breeds on test images
8. Generate Kaggle submission file

---

## 📁 Project Structure

```text
Dog-Breed-Identification/
│
├── dog_Breed-Identification.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── screenshots/
└── models/
```

---

## 📈 Results

* Successfully trained a deep learning model for multi-class dog breed classification.
* Generated predictions for the Kaggle Dog Breed Identification competition.
* Achieved a competitive Kaggle leaderboard score.

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/okavthekar-dev/Dog-Breed-Identification.git
```

Move into the project directory:

```bash
cd Dog-Breed-Identification
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## 💻 Development Environment

This project was developed and trained using **Google Colab** with GPU acceleration.

You can open the notebook directly in Google Colab or Jupyter Notebook if all required dependencies are installed.

---

## 📌 Future Improvements

* Fine-tune the pretrained model
* Experiment with EfficientNet and other architectures
* Apply advanced data augmentation
* Deploy the model using Streamlit or Flask
* Convert the model to TensorFlow Lite for mobile applications

---

## 🙏 Acknowledgements

* Kaggle Dog Breed Identification Dataset
* TensorFlow
* TensorFlow Hub
* Keras

---

## 👨‍💻 Author

**Omkar Kavathekar**

 Machine Learning & Deep Learning Enthusiast

If you found this project helpful, consider giving it a ⭐ on GitHub!
