<!-- # Dataset Link - 
<a href="https://www.kaggle.com/datasets/sayaniiitian/dr-datasets">Kaggle</a>

# Contributors -
<a href="https://github.com/AmitMandhana">Amit Mandhana</a>
<span>&nbsp;&nbsp;&nbsp;&nbsp;</span>
<a href="https://github.com/prithwish2dey">Prithwish Dey</a>
<span>&nbsp;&nbsp;&nbsp;&nbsp;</span>
<a href="https://github.com/sayan-iiitian">Sayan Mandal</a>
<span>&nbsp;&nbsp;&nbsp;&nbsp;</span>
<a href="https://github.com/chirag21r">Chirag Shukla</a> -->

# 🩺 Diabetic Retinopathy Classification using Deep Learning

This project presents a comprehensive deep learning pipeline to classify **Diabetic Retinopathy (DR)** severity from retinal fundus images. We explore multiple CNN-based architectures including a custom CNN, **ResNet152**, and **EfficientNetV2B0**, comparing their performance under transfer learning and fine-tuning strategies.

---

## 🚀 Project Overview

- **Goal**: To detect and classify the severity of Diabetic Retinopathy from retinal images using deep learning.
- **Models Used**: 
  - Custom CNN (built from scratch)
  - ResNet152 (Transfer Learning & Fine-Tuning)
  - EfficientNetV2B0 (with Compound Scaling)
- **Techniques**:
  - Transfer learning & fine-tuning
  - Data preprocessing & augmentation
  - Loss function analysis
  - Training visualization: accuracy/loss plots & confusion matrix

---

## 📂 Dataset

- The dataset contains labeled retinal fundus images categorized into five DR severity classes: **Normal**, **Mild**, **Moderate**, **Severe**, and **Proliferative DR**.
- 📎 Dataset Link:  
  👉 [Kaggle - DR Datasets](https://www.kaggle.com/datasets/sayaniiitian/dr-datasets)

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- Matplotlib & Seaborn
- Jupyter Notebook
- Overleaf (for documentation)
- LaTeX

---

## 👨‍💻 Contributors

- [Amit Mandhana](https://github.com/AmitMandhana)  
- [Prithwish Dey](https://github.com/prithwish2dey)  
- [Sayan Mandal](https://github.com/sayan-iiitian)  
- [Chirag Shukla](https://github.com/chirag21r)  

---

## 📄 Documentation

All code, notebooks, and the LaTeX report (Overleaf) are included in this repository for reference and reproducibility.

---

## 📌 Results Summary

| Model              | Fine-Tuned | Accuracy | Speed    | Parameters |
|-------------------|------------|----------|----------|------------|
| Custom CNN         | ❌         | Medium   | Fast     | Low        |
| ResNet152          | ✅ (50L)   | High     | Moderate | High       |
| EfficientNetV2B0   | ✅ (30L)   | Very High| Slower   | Moderate   |

---

## 💡 Future Scope

- Integration with mobile or web-based diagnosis tools
- Explainability (Grad-CAM visualizations)
- Expanded dataset for improved generalization

---

⭐ If you find this useful, consider giving the repo a star!


