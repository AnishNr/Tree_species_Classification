# 🌳 Tree Intelligence Assistant (Tree Species Classification)

This **AI-powered app** helps students and nature enthusiasts identify and explore tree species based on **image**, **location**, and **tree attributes**.

---

## 🧠 Features

- 🌲 **Recommend Trees by Location**  
- 📍 **Find Locations for a Tree**  
- 📷 **Identify Tree from Image**

---

## 📊 Dataset Description

- 🗂️ **Tree Metadata**  
- 🖼️ **Tree Image Dataset**  
- 📁 **[Download Dataset from Google Drive](https://drive.google.com/drive/folders/1R8ENaxi4sryzu7c4jOE-9xFisjs1qasi?usp=sharing)**

> _Due to large file size, the dataset is hosted externally on Google Drive._

---

## 🧪 Algorithms Used

- 🔍 **Recommender System**  
- 🧠 **CNN Classifier**  
- 📊 **Preprocessing & Encoding**

---
🔗 [Download `.h5` Model Files from Google Drive](https://drive.google.com/drive/folders/1R8ENaxi4sryzu7c4jOE-9xFisjs1qasi?usp=sharing)

## 📥 How to Use the Dataset in Google Colab

```python
# Install gdown (if not already installed)
!pip install -U gdown

# Download individual files from the shared folder manually by ID
# OR mount Google Drive and copy files directly

from google.colab import drive
drive.mount('/content/drive')

# Now access files from your Google Drive like:
# /content/drive/MyDrive/path_to_dataset_folder
