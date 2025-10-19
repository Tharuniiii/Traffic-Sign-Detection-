# 🛣️ Traffic Sign Detection using Deep Learning
🚦 Traffic Sign Detection using Deep Learning — a Python Tkinter app powered by a CNN trained on the GTSRB dataset. Users can upload an image, and the system predicts the traffic sign label in real time.

# 🚦 Features

🧠 Deep Learning Model (trained on the German Traffic Sign Recognition Benchmark - GTSRB)

🖼️ User-Friendly GUI using Tkinter

📁 Image Upload & Preview before classification

⚡ Real-Time Prediction with confidence output

🎯 Supports 43 traffic sign categories

# 🧩 Tech Stack
```bash
| Component             | Technology                              |
| --------------------- | --------------------------------------- |
| Programming Language  | Python 3.10+ (works with 3.12/3.13 too) |
| GUI Framework         | Tkinter                                 |
| Deep Learning         | TensorFlow / Keras                      |
| Image Processing      | PIL (Pillow)                            |
| Numerical Computation | NumPy                                   |
```

# 🧠 Dataset

The model was trained on the GTSRB (German Traffic Sign Recognition Benchmark) dataset, which includes over 50,000 images of 43 different traffic sign classes.
# 📦 Dataset source:
https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

# ⚙️ Installation and Setup
1️⃣ Clone the repository
```
git clone https://github.com/your-username/traffic-sign-detection.git
cd traffic-sign-detection
```
2️⃣ Install dependencies
```
pip install tensorflow pillow numpy
```
3️⃣ Add your trained model
```
traffic-sign-detection/
│
├── my_model.h5
├── gui.py
├── README.md
└── sample_images/
```

4️⃣ Run the GUI,traffic_sign.py

# 🖥️ How It Works

Click "Upload an image" in the GUI.

Select a traffic sign image (e.g., stop sign).

Click "Classify Image".

The system predicts and displays the traffic sign label.

# sample output
<img width="1202" height="923" alt="Screenshot 2025-10-19 122654" src="https://github.com/user-attachments/assets/f274c4ca-997b-44e3-9d1c-f025b062c7f6" />

# 🧰 File Structure
```
traffic-sign-detection/
│
├── gui.py                # Main GUI application
├── my_model.h5           # Pre-trained CNN model
├── README.md             # Project documentation
├── sample_images/        # Test images
└── requirements.txt      # (Optional) dependencies
```

# 🚀 Future Enhancements

Add model training notebook for fine-tuning.

Include confidence score visualization.

Extend support for real-time detection via webcam (OpenCV).

Create a web-based version using Streamlit or Flask.
