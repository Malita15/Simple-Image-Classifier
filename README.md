# 🖼️ Simple Image Classifier

A simple image classifier that uses the **EfficientNetB0** model to classify images from the **Kaggle Cats vs Dogs dataset**.

## 🚀 Features

- Uses **EfficientNetB0** for feature extraction
- Loads and preprocesses images from **Kaggle’s Cat vs Dog dataset**
- Classifies images into **Cats** or **Dogs** with high accuracy
- Supports **real-time image testing**

## 📂 Dataset

You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset?resource=download).

### 📥 Download via Kaggle API

1. Install Kaggle API:
    ```bash
    pip install kaggle
    ```

2. Move your **kaggle.json** file to the correct location:
    ```bash
    mkdir ~/.kaggle
    mv /path/to/kaggle.json ~/.kaggle/
    chmod 600 ~/.kaggle/kaggle.json
    ```

3. Now, download the dataset:
    ```bash
    kaggle datasets download -d karakaggle/kaggle-cat-vs-dog-dataset
    unzip kaggle-cat-vs-dog-dataset.zip -d dataset
    ```

## 🛠️ Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Simple-Image-Classifier.git
    cd Simple-Image-Classifier
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Mac/Linux
    env\Scripts\activate     # On Windows
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## 🖥️ Usage

To run the classifier:

```bash
python image_recognition.py
```

## 🏗️ Folder Structure:
```bash
Simple-Image-Classifier/  
│── dataset/               # Dataset folder  
│── src/                   # Source code  
│   ├── image_recognition.py  # Main script  
│── README.md              # Project documentation  
│── requirements.txt       # Dependencies
```

## ❤️ Contributing:
Feel free to open issues or submit pull requests!
