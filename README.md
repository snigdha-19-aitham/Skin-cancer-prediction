# Skin Cancer Prediction Using Deep Learning

This project aims to build a deep learning-based system for automated skin cancer classification using Convolutional Neural Networks (CNNs). The model classifies dermoscopic images into multiple skin lesion categories, such as melanoma, benign keratosis, and others. A Flask web application is also integrated to allow users to upload images and receive instant predictions.

---

## 🔍 Project Highlights

- Utilizes Convolutional Neural Networks (CNN) for accurate image classification.
- Classifies images into categories such as melanoma, basal cell carcinoma, benign keratosis, etc.
- Flask-based web app for easy image upload and instant predictions.
- Real-time predictions with confidence scores and result interpretation.

---

## 📁 Dataset Requirement

This project uses the **[HAM10000 Dataset](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)** (Human Against Machine with 10000 training images) available on Kaggle.

**Important: You must download the HAM10000 dataset manually.**

### Files required:

- `HAM10000_metadata.csv` – Metadata file with labels
- `HAM10000_images_part_1.zip` and `HAM10000_images_part_2.zip` – Image data

### How to Use:

1. Download the dataset from Kaggle.
2. Extract all images into a single folder named `HAM10000_images/`.
3. Place the `HAM10000_metadata.csv` in the root folder of the project or update the script paths accordingly.

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Flask (for web interface)

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/snigdha-19-aitham/skin-cancer-prediction.git
   cd skin-cancer-prediction
