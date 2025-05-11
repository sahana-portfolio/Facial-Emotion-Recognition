😄 Facial Emotion Recognition Web App
A machine learning project that detects and classifies human facial expressions such as Happy, Sad, Angry, Surprised, and more, using a CNN model trained on the FER-2013 dataset. Built with Python, TensorFlow/Keras, and deployed using Streamlit.

## 📂 Dataset
The `fer2013.csv` dataset used in this project can be downloaded from the link below:

👉 [FER-2013 dataset](https://www.kaggle.com/datasets/msambare/fer2013).  
Download `fer2013.csv` manually and place it in the root project folder.


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
- Streamlit 

## 📂 Project Structure
Facial_Emotion_Recognition_Project/
├── app.py                          # Streamlit UI app
├── model.h5                        # Trained CNN model
├── requirements.txt                # Dependencies
├── README.md                       # Project documentation
│
├── utils/                          # Helper functions
│   └── preprocessing.py            # (optional)
│
├── screenshots/                    # App UI screenshots
│   ├── ss-1.png                    # Screenshot 1 - App UI
│   ├── ss-2.png                    # Screenshot 2 - Model Output
│   └── ss-3.png                    # Screenshot 3 - Real-time Detection
│
├── csv_to_images.py                # Converts CSV dataset to image files
├── train_model.py                  # CNN training script
└── live_emotion_detector.py        # Real-time emotion detector using webcam


## 🧠 How It Works
1.csv_to_images.py: Converts fer2013.csv into folders of images by emotion label.

2.train_model.py: Trains the CNN model on the converted images.

3.live_emotion_detector.py: Launches webcam and predicts emotion live.

4.app.py: Launches the Streamlit web interface for predictions.

## 📸 Sample Output

 Screenshot -1 (![ss-1](https://github.com/user-attachments/assets/b4851a60-e2c4-4974-bba7-9a2d25a73f8c)
)
screenshot-2 ![ss-2](https://github.com/user-attachments/assets/dfc74c24-0820-4dc3-a345-0e33966c215c)
screenshot-3 ![ss-3](https://github.com/user-attachments/assets/1d37977e-25c1-4dbc-b825-296ce2c1468c)




## ✅ To Run the Project

# Step 1: Install required packages
pip install -r requirements.txt

# Step 2: Convert dataset to images (only once)
python csv_to_images.py

# Step 3: Train the CNN model
python train_model.py

# Step 4: Test real-time emotion detection
python live_emotion_detector.py

# Optional: Run the Streamlit UI app
streamlit run app.py

🙋 About Me

Sahana L
B.E. Computer Science | HKBK College of Engineering
AWS Cloud | AI/ML | GitHub Portfolio
 
