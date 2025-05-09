# Facial Emotion Recognition 😄😠😢😲

This is a machine learning project that detects and classifies human facial expressions into emotions like **Happy**, **Sad**, **Angry**, **Surprised**, and more using a CNN-based model trained on the **FER-2013** dataset.

## 🚀 Features

- Real-time emotion detection using webcam 🎥
- CNN model trained on FER-2013 dataset
- Live prediction overlay using OpenCV
- Converts CSV dataset to image format for model training
- Clean modular code with easy-to-understand logic

## 🛠️ Tech Stack

- Python 🐍
- OpenCV
- TensorFlow / Keras
- NumPy, Pandas
- Streamlit (if UI is included)

## 📂 Project Structure
├── app.py # Main app (UI or interface)
├── live_emotion_detector.py # Real-time emotion detection
├── train_model.py # CNN training script
├── csv_to_images.py # Converts CSV to image files
├── dataset/ # FER-2013 CSV and generated images
├── models/ # Trained CNN model
├── images/ # Sample/test images
└── README.md


## 🧠 How It Works

1. `csv_to_images.py` converts the FER-2013 CSV into image files sorted by emotion.
2. `train_model.py` trains a CNN model on this image data.
3. `live_emotion_detector.py` uses the webcam feed to predict emotions live.
4. `app.py` provides a user interface (if implemented using Streamlit or Tkinter).

## 📸 Sample Output

> *(Add a screenshot or GIF here if possible to show real-time detection)*

## ✅ To Run the Project

```bash
# Step 1: Install dependencies
pip install -r requirements.txt

# Step 2: Convert CSV to image dataset (run only once)
python csv_to_images.py

# Step 3: Train the model
python train_model.py

# Step 4: Run real-time emotion detection
python live_emotion_detector.py

Sahana L
B.E. Computer Science | HKBK College of Engineering
AWS Cloud | AI/ML | GitHub Portfolio
 
