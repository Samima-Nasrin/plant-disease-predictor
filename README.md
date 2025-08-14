# Plant Disease Classification using CNN

This project is a **Convolutional Neural Network (CNN)** based deep learning application for classifying plant diseases from leaf images using the **PlantVillage dataset**.  
It downloads the dataset from Kaggle, preprocesses it, trains a CNN model, and allows predictions on custom images.  
The model can also be deployed with **Streamlit** for an interactive web interface.

---

## Features
- **Download & extract** PlantVillage dataset from Kaggle automatically.
- **Data preprocessing** using `ImageDataGenerator`.
- **CNN model** for classification of plant leaf diseases.
- **Accuracy & loss visualization** during training.
- **Prediction function** for custom images.
- Saves:
  - `plant_disease_prediction_model.h5` → trained model
  - `class_indices.json` → label mappings
- Can be integrated with a **Streamlit frontend** for user-friendly classification.

---

## Dataset

The dataset used is the **PlantVillage Dataset** from Kaggle:  
[kaggle.com/datasets/emmarex/plantdisease](https://www.kaggle.com/datasets/emmarex/plantdisease)
