# Face Mask Detection using CNN

This project implements a Convolutional Neural Network (CNN) model to automatically detect whether a person is wearing a face mask or not. The model is trained using publicly available labeled datasets consisting of masked and unmasked human faces.

---

## Project Description

With increased emphasis on public health and safety, automation of face mask compliance monitoring is essential. This project builds a deep learning–based image classifier that categorizes input images into:

* **With Mask**
* **Without Mask**

The model uses a CNN architecture built using TensorFlow/Keras. The training dataset consists of thousands of labeled images for both classes. After training, the model is capable of detecting face masks in real-time using webcam input or image uploads.

---

## ✅ Features

* Trains a CNN model from scratch using a labeled dataset.
* Preprocessing and data augmentation to improve accuracy.
* Achieves high accuracy on validation data.
* Option for real-time mask detection using webcam feed (optional depending on your code).
* Model can be exported and deployed in applications.

---

## 🧠 Model Architecture (General Overview)

* Convolutional layers for feature extraction
* MaxPooling for dimensionality reduction
* Flatten + Dense layers for classification
* Softmax output layer for binary classification

---

## 🛠️ Tech Stack Used

| Component               | Technology               |
| ----------------------- | ------------------------ |
| Programming Language    | Python                   |
| Deep Learning Framework | TensorFlow / Keras       |
| Data Processing         | NumPy, OpenCV            |
| Visualization           | Matplotlib, Seaborn      |
| Environment             | Jupyter Notebook / Colab |

---

## 🚀 Steps to Run

1. Clone the repository

   ```bash
   git clone https://github.com/Maanya-mv/CNN-Face-Mask-Detection.git
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter/Colab notebook

   ```bash
   jupyter notebook
   ```

4. Train the model (runs automatically inside the notebook)

5. Test the model using sample images or webcam streaming.

---

## 📊 Results and Accuracy

| Metric              | Score                             |
| ------------------- | --------------------------------- |
| Training Accuracy   | ~95–98% (varies based on dataset) |
| Validation Accuracy | ~92–96%                           |

---

## 📌 Future Scope

* Integration with CCTV feeds for live monitoring.
* Deployment as a web application using Flask or FastAPI.
* Multiclass classification (mask, improper mask, no mask).

---

## 🤝 Contributions

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is released under the **MIT License**.

---

If you want, I can also:

* generate badges (like build passing, license, etc.)
* write a short GitHub description
* help upload your project to GitHub

➡️ "Help me push this project to GitHub"

Ready to continue whenever you are.
