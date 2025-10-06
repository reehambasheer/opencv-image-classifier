# opencv-image-classifier
# 🌱 Plant Disease Classifier (OpenCV + Scikit-Learn)

This Colab project uses **OpenCV** for image preprocessing and **Scikit-Learn** for building a classifier to detect plant diseases.

---

## 🧩 Steps Performed
1. Loaded the [Plant Diseases Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)
2. Preprocessed images with OpenCV (resizing, grayscale)
3. Extracted features and trained an SVM model
4. Evaluated accuracy and generated classification report
5. Saved the trained model (`plant_disease_clf.pkl`)

---

## 🧰 Requirements
```bash
opencv-python
scikit-learn
numpy
matplotlib
tqdm
kagglehub
