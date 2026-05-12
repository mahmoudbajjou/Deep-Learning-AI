# Deep Learning & Artificial Intelligence Laboratory

This repository contains a series of advanced laboratories focused on modern neural network architectures. Each project is implemented using **PyTorch** and covers the complete pipeline: data preprocessing, model architecture design, training loops, and performance evaluation.

---

## 📂 Project Portfolio

### 1. [Multi-Layer Perceptron (MLP) for Tabular Data](MLP_IA_MahmoudBAJJOU.ipynb)
* **Dataset:** *Dry Bean Dataset* (UCI Machine Learning Repository).
* **Description:** Implemented a deep MLP to classify various types of dry beans based on geometric and texture features.
* **Technical Highlights:**
    * Data manipulation with `Pandas` and feature normalization.
    * Creating custom PyTorch `Dataset` and `DataLoader` classes.
    * Building a multi-class classification model using `nn.Module`.
    * Analyzing the impact of activation functions (ReLU, Sigmoid) and hidden layer depth.

### 2. [Convolutional Neural Networks (CNN) for Computer Vision](CNN_Mahmoud_BAJJOU.ipynb)
* **Datasets:** MNIST (Handwritten digits) and CIFAR-10 (Object categories).
* **Description:** Exploration of spatial feature extraction through convolutional layers.
* **Technical Highlights:**
    * Building a CNN architecture from scratch (Conv2D, MaxPool, Linear).
    * **Regularization:** Implementing **Dropout** and **Batch Normalization** to prevent overfitting.
    * **Data Augmentation:** Using `torchvision.transforms` (Rotation, Flip, Color Jitter) to improve model robustness.
    * **Transfer Learning:** Fine-tuning a pre-trained **ResNet18** model for advanced image classification.

### 3. [RNN Part I: Sentiment Analysis (Many-to-One)](RNN_1_Mahmoud.ipynb)
* **Dataset:** IMDB Movie Reviews.
* **Description:** Natural Language Processing (NLP) task to classify movie reviews as positive or negative.
* **Technical Highlights:**
    * Text preprocessing: Tokenization, building a vocabulary, and padding sequences.
    * **Embedding Layer:** Transforming discrete words into dense vector spaces.
    * **Architectural Comparison:** Benchmarking standard **RNN** cells against **LSTM** (Long Short-Term Memory) units to handle vanishing gradients.

### 4. [RNN Part II: Sequence Generation (One-to-Many)](RNN_2_Mahmoud.ipynb)
* **Topic:** Music Generation (J.S. Bach Cello Suites).
* **Description:** Building a "Language Model" for music. The model learns the patterns of Bach's compositions to generate original musical sequences.
* **Technical Highlights:**
    * **Symbolic Data Handling:** Converting MIDI files into One-Hot encoded vectors.
    * **Generative Modeling:** Implementing a sampling strategy to predict the next note based on the previous sequence.
    * Exploring the temperature parameter to control the "creativity" of the output.

---

## 🛠 Tech Stack
* **Core Framework:** `PyTorch`
* **Vision & Audio:** `torchvision`, `pretty_midi`
* **Analysis:** `NumPy`, `Pandas`, `Matplotlib`, `Seaborn`
* **Environment:** Jupyter Notebooks / Google Colab (GPU accelerated)

## 🚀 How to Run
1.  Clone the repo:
    ```bash
    git clone [https://github.com/YourUsername/Deep-Learning-AI.git](https://github.com/YourUsername/Deep-Learning-AI.git)
    ```
2.  Install requirements:
    ```bash
    pip install torch torchvision pandas numpy matplotlib scipy
    ```
3.  Launch Jupyter Lab or Notebook:
    ```bash
    jupyter lab
    ```

---
**Author:** Mahmoud Bajjou
