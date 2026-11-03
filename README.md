# ✍️ Handwritten Digit Recognition using CNN

A Deep Learning project that uses a **Convolutional Neural Network (CNN)** to recognize and classify handwritten digits (0–9) from images.

The project explores how deep learning and computer vision can be used to automatically identify handwritten numbers with high accuracy.

---

## 📌 Project Overview

Handwritten digit recognition is a classic computer vision problem that involves identifying numerical digits from handwritten images.

In this project, a CNN model is developed and trained to learn patterns, edges, and features from handwritten digit images and classify them into their corresponding numerical categories.

The model aims to provide accurate predictions while demonstrating the practical application of Convolutional Neural Networks in image classification.

## 🎯 Objectives

* Build a CNN-based handwritten digit recognition system.
* Understand image preprocessing and normalization.
* Extract meaningful image features using convolutional layers.
* Train and evaluate a deep learning model.
* Predict handwritten digits from input images.

## 🛠️ Tech Stack

| Technology         | Purpose                              |
| ------------------ | ------------------------------------ |
| Python             | Programming language                 |
| TensorFlow / Keras | Deep learning and CNN implementation |
| NumPy              | Numerical computations               |
| Matplotlib         | Data visualization                   |
| Google Colab       | Cloud-based development environment  |

## 🧠 CNN Architecture

The Convolutional Neural Network consists of the following layers:

1. **Convolutional Layer** – Extracts important features from input images.
2. **Activation Function (ReLU)** – Introduces non-linearity into the network.
3. **Pooling Layer** – Reduces feature map dimensions while retaining important information.
4. **Flatten Layer** – Converts extracted features into a one-dimensional vector.
5. **Dense Layer** – Learns patterns for classification.
6. **Output Layer** – Predicts one of the ten digit classes (0–9).

## 📂 Project Structure

```text
Handwritten-Digit-recognition-using-CNN/
│
├── README.md
├── Handwritten_Digit_Recognition.ipynb
│
└── .gitignore
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Ankitajena12/Handwritten-Digit-recognition-using-CNN.git
```

### 2. Navigate to the Project Directory

```bash
cd Handwritten-Digit-recognition-using-CNN
```

### 3. Install Dependencies

```bash
pip install tensorflow numpy matplotlib
```

### 4. Run the Notebook

Open the `.ipynb` file using Jupyter Notebook or Google Colab and execute the cells sequentially.

**Google Colab:** You can also open the notebook directly in Google Colab to run the project without setting up a local environment.

## 📊 Results

The model is evaluated using classification accuracy and loss.

Evaluation metrics and visualizations can be added here after training the model.

## 🔮 Future Improvements

* Improve model accuracy through hyperparameter tuning.
* Test the model on custom handwritten digit images.
* Experiment with different CNN architectures.
* Build a simple web interface for real-time digit prediction.

## 👩‍💻 Author

**Ankita Jena**

* GitHub: [@Ankitajena12](https://github.com/Ankitajena12)

---

⭐ If you find this project interesting, consider giving the repository a star!
