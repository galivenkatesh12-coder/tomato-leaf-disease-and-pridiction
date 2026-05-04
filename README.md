# 🍅 Tomato Leaf Disease Prediction

## 📌 Project Overview

This project focuses on building a **Tomato Leaf Disease Prediction System** using machine learning and deep learning techniques. The system analyzes images of tomato leaves and classifies them into healthy or diseased categories, helping in early detection and prevention of crop loss.

---

## 👨‍🎓 Student Details

* **Name:** venkatesh.gali
* **Student ID:** 2863280
* **Course:** MSc Artificial Intelligence

---

## 🎯 Objectives

* Detect and classify diseases in tomato leaves from images
* Improve prediction accuracy using deep learning models
* Support early diagnosis for better agricultural outcomes

---

## 🧠 Technologies Used

* Python
* TensorFlow / Keras or PyTorch
* OpenCV
* NumPy & Pandas
* Matplotlib

---

## 📂 Dataset

This project uses the **Tomato Leaves Dataset**, which contains labeled images of tomato plant leaves.

### Dataset Features:

* Images categorized into multiple classes such as:

  * Healthy leaves
  * Early Blight
  * Late Blight
  * Leaf Mold
  * Septoria Leaf Spot
  * Bacterial Spot

* The dataset is widely used for plant disease classification tasks and is suitable for training deep learning models like CNNs.

---

## ⚙️ Methodology

1. **Data Collection**

   * Use Tomato Leaves Dataset

2. **Data Preprocessing**

   * Image resizing (e.g., 224x224)
   * Normalization
   * Data augmentation (rotation, flipping, zooming)

3. **Model Building**

   * Convolutional Neural Network (CNN)
   * Optionally use transfer learning (e.g., VGG16, ResNet50)

4. **Training**

   * Train/test split
   * Model training with validation

5. **Evaluation**

   * Accuracy
   * Confusion Matrix
   * Precision, Recall, F1-score

6. **Prediction**

   * Input: tomato leaf image
   * Output: predicted disease class

---

## 📊 Results

* The model achieves strong performance in classifying tomato leaf diseases (accuracy depends on training setup and dataset size).
* Effective in distinguishing between multiple disease categories.

---

## 🚀 Future Improvements

* Deploy as a web or mobile application
* Real-time detection using camera input
* Improve accuracy with larger datasets
* Add disease treatment suggestions

---

## 📁 Project Structure

```id="k29x81"
Tomato-Leaf-Disease-Prediction/
│
├── dataset/
├── models/
├── notebooks/
├── src/
├── results/
├── README.md
```

---

## ▶️ How to Run

1. Clone the repository

   ```
   git clone <repository-link>
   ```

2. Install dependencies

   ```
   pip install -r requirements.txt
   ```

3. Train the model

   ```
   python train.py
   ```

4. Run prediction

   ```
   python predict.py
   ```

---

## 📜 License

This project is for academic purposes.

---

## 🙏 Acknowledgements

* Tomato Leaves Dataset
* Open-source machine learning community

---
