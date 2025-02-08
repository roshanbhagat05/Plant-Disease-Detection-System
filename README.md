# 🌿 Plant Disease Detection System

## 📌 Overview
The **Plant Disease Detection System** is an AI-based solution that utilizes **Deep Learning and Computer Vision** to detect diseases in plant leaves. The system employs **Convolutional Neural Networks (CNNs)** trained on a dataset of diseased and healthy leaves to classify plant diseases accurately. 

## ✨ Features
- **Deep Learning Model:** Uses CNN architecture for high accuracy.
- **Multi-Class Classification:** Detects various plant diseases.
- **User Interface:** Streamlit-based web application for easy use.
- **Image Processing:** Supports real-time detection and analysis.
- **Scalability:** Can be expanded to support more plant species and diseases.

## 📂 Dataset
The model is trained on the **PlantVillage dataset**, which contains thousands of images of healthy and diseased plant leaves. The dataset includes:
- Apple Scab
- Black Rot
- Powdery Mildew
- Tomato Leaf Spot
- Healthy Leaves, and more...

## 📊 Model Architecture
The model is built using **TensorFlow** and **Keras**. It consists of:
- **Convolutional Layers** for feature extraction.
- **MaxPooling Layers** to reduce dimensionality.
- **Fully Connected Layers** for classification.
- **Softmax Activation** for multi-class prediction.

## 🛠 Installation & Setup
Follow these steps to set up the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/roshanbhagat05/Plant-Disease-Detection-System.git
cd Plant-Disease-Detection-System
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Install TensorFlow and Streamlit
```bash
pip install tensorflow streamlit
```

### 4️⃣ Run the Streamlit Application
```bash
streamlit run app.py
```

## 🚀 Usage
1. Upload an image of a plant leaf.
2. The system processes the image and predicts the disease (if any).
3. It provides recommendations for disease control and treatment.

## 🖥 Technologies Used
- **Python**
- **TensorFlow/Keras**
- **OpenCV**
- **Streamlit**
- **Git & GitHub**

## 🔥 Results & Performance
The model achieves **high accuracy** on the test set with efficient real-time predictions. Performance metrics:
- **Accuracy:** ~92%
- **Precision & Recall:** Optimized for multi-class classification.

## ⚡ Future Enhancements
- Expand the dataset with more plant species.
- Integrate a **mobile application** for easy accessibility.
- Improve model efficiency with **transfer learning** techniques.

## 📜 License
This project is open-source under the **MIT License**.

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## 📧 Contact
For queries or collaborations:
📩 Email: roshanbhagatbysiness2005@gmail.com
📌 GitHub: https://github.com/roshanbhagat05
🔗 Linkedin: www.linkedin.com/in/roshanbhagat2005

---
🌱 *Let's build a healthier and more sustainable agriculture system with AI!* 🚀
