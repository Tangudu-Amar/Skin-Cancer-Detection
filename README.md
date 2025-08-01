
# 🧠 Skin Cancer Detection System using CNN + Streamlit

This project is an end-to-end skin cancer detection system that classifies skin lesion images as **Benign** or **Malignant** using a **Convolutional Neural Network (CNN)** and provides predictions through a **Streamlit-based web app**.

---

## 📁 Project Structure

```
SKIN_CANCER_DETECTION/
│
├── melanoma_cancer_dataset/     # Contains train/test image folders
├── app.py                       # Streamlit app for deployment
├── final1.ipynb                 # Jupyter Notebook for training the model
├── model123.h5                  # Trained CNN model (Keras .h5 format)
├── model123.keras               # (Optional) Another model save format
└── requirements.txt             # Required Python packages
```

---

## 🚀 Features

- Built using **TensorFlow/Keras**
- Classifies input images into:
  - ✅ **Benign (Non-cancerous)**
  - ⚠️ **Malignant (Cancerous)**
- Provides **confidence score (%)**
- Web interface using **Streamlit**
- User-friendly and easy to run

---

## 🧪 How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/Tangudu-Amar/skin-cancer-detection.git
cd skin-cancer-detection
```

### 2. Set Up a Virtual Environment (Recommended)

```bash
python -m venv venv
source venv/bin/activate    # On Windows use: venv\Scripts\activate
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit App

```bash
streamlit run app.py
```

---

## 🖼️ Using the Web App

1. Upload a skin lesion image (`.jpg`, `.jpeg`, `.png`).
2. View the predicted class (Benign or Malignant).
3. See the confidence score displayed in a table.

---

## 📊 Model Training

- Training was done using `final1.ipynb`:
  - Dataset split: 80% Train / 20% Validation
  - Image size: `256x256`
  - Data augmentation: `RandomFlip`, `RandomRotation`
  - CNN model: Conv2D + MaxPooling + Flatten + Dense + Softmax
- Final model saved as: `model123.h5`

---

## 💡 Future Improvements

- Add support for multiple skin conditions
- Use transfer learning (e.g., MobileNet, EfficientNet)
- Improve UI with probability charts
- Deploy publicly via Streamlit Cloud or Hugging Face Spaces

---


## 👨‍💻 Author

**Amar Tangudu**   
Email: amartangudu2004.2@gmail.com

---
