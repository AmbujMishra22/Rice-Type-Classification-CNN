# 🌾 Rice Type Classification using CNN

## 📌 Overview

This project focuses on classifying different types of rice grains using **Convolutional Neural Networks (CNNs)**. The model is trained on image data to automatically identify rice varieties with high accuracy, making it useful for agriculture, quality control, and food industry applications.

---

## 🚀 Features

* 📷 Image-based rice classification
* 🧠 Deep Learning model using CNN
* ⚡ Real-time prediction using Flask API
* 📊 Data preprocessing and augmentation
* 📈 Model evaluation with accuracy and loss graphs

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries/Frameworks:** TensorFlow, Keras, NumPy, Pandas, OpenCV
* **Backend:** Flask
* **Tools:** Jupyter Notebook, VS Code

---

## 📂 Project Structure

```
Rice-Classification/
│── dataset/
│── model/
│   └── rice_model.h5
│── app.py
│── train.py
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/rice-classification.git
cd rice-classification
```

### 2️⃣ Create virtual environment

```bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🧪 Model Training

```bash
python train.py
```

* Loads dataset
* Applies preprocessing
* Trains CNN model
* Saves trained model (`.h5` file)

---

## ▶️ Run the Application

```bash
python app.py
```

* Starts Flask server
* Upload rice image
* Returns predicted rice type

---

## 🧠 Model Details

* Convolutional layers for feature extraction
* MaxPooling layers for dimensionality reduction
* Fully connected dense layers
* Softmax activation for classification

---

## 📊 Results

* Achieved high accuracy on validation dataset
* Efficient classification of multiple rice varieties

---

## 📸 Sample Output

* Input: Rice grain image
* Output: Predicted rice type (e.g., Basmati, Jasmine, etc.)

---

## 📈 Future Improvements

* Improve accuracy using transfer learning
* Deploy on cloud (AWS/Heroku)
* Add mobile app integration
* Expand dataset for better generalization

---

## 📄 License

This project is for educational purposes.

---
