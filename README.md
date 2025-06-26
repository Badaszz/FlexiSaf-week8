# FlexiSaf-week8
Body Language Detector is a machine learning project that uses Media Pipe to extract human pose and facial landmarks from images or video streams, and classifies the person's body language all implemented in Python and Jupyter Notebook.

# 🧍‍♂️ Body Language Detector Using MediaPipe + Random Forest
---

## 📌 Features

- Extracts **pose** and **face** landmarks using MediaPipe
- Classifies human **body language** (e.g., *confident*, *nervous*, *relaxed*) using a trained model
- Visualizes predictions on images
- Built with Python, OpenCV, scikit-learn, and Jupyter Notebook

---

## 🧠 Classes

Currently trained on:
- Anxious
- Folded Arms
- Drowsy

---

## 🗂️ Project Structure

```
.
├── BodyLanguageDetector.ipynb     # Main notebook (training + testing + video prediction)
├── model/
│   └── pose_face_rf_model.pkl     # Trained RandomForest model
├── data/
│   └── body_language_dataset.csv  # Extracted features + labels
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

### 1. Clone the repo
```bash
git clone https://github.com/your-username/BodyLanguageDetector.git
cd BodyLanguageDetector
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the notebook
```bash
jupyter notebook BodyLanguageDetector.ipynb
```

---

## 📊 Dataset

The dataset was **custom-collected** and stored in:
```
data/body_language_dataset.csv
```

It contains:
- 99 pose features (33 landmarks × x, y, z)
- 1404 face features (468 landmarks × x, y, z)
- Label column (`label`)

---

## 🧪 Model

The model is trained using `RandomForestClassifier` from scikit-learn and saved to:
```
model/pose_face_rf_model.pkl
```

---



## 🧑‍💻 Author

**Yusuf Solomon**  
[LinkedIn](https://linkedin.com/in/yusuf-solomon) 

---

