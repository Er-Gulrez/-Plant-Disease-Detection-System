# 🌿 Plant Disease Detection System

A deep learning-based web application that detects and classifies plant diseases from leaf images using **VGG16** and **transfer learning**, helping farmers and agricultural experts make informed decisions.

---

## 📌 Overview

The Plant Disease Detection System is a smart AI-powered solution that allows users to:

- 📸 Upload images of infected plant leaves
- 🧠 Detect the type of disease using a CNN model
- 🩺 Get treatment suggestions and prevention tips
- 🌱 Support sustainable and healthy farming practices

Developed as part of the final year engineering project at **SSBT’s College of Engineering and Technology**, Jalgaon.

---

## 🎯 Objectives

- Build a high-accuracy plant disease classifier using VGG16
- Create a simple web app using **Streamlit**
- Assist farmers with disease recognition and remedies
- Enable early detection with minimal resources

---

## 🛠️ Tech Stack

| Layer        | Tools Used                  |
|--------------|-----------------------------|
| Frontend     | Streamlit                   |
| Backend      | Python                      |
| ML Framework | TensorFlow, Keras           |
| Image Tools  | OpenCV                      |
| Libraries    | NumPy, Matplotlib, Seaborn  |
| Database     | MySQL (optional)            |

---

## 🧠 Model Details

- **Architecture**: VGG16 (pre-trained on ImageNet, fine-tuned on plant disease dataset)
- **Layers**:
  - 13 Conv Layers
  - 5 MaxPool Layers
  - 3 Fully Connected Layers
- **Image Input Size**: 224x224
- **Accuracy**: ~98%
- **Processing Time**: 3–5 seconds per image

---

## 📂 Folder Structure

```
plant-disease-detection-system/
│
├── model/
│   └── vgg16_trained_model.h5       # Trained model
├── data/
│   └── sample_images/               # Test samples
├── app.py                           # Streamlit app
├── predict.py                       # Prediction logic
├── preprocess.py                    # Image processing
├── requirements.txt                 # Dependencies
└── README.md                        # Documentation
```

---

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/plant-disease-detection-system.git
   cd plant-disease-detection-system
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**:
   ```bash
   streamlit run app.py
   ```

4. **Upload an image and get prediction!**

---

## 📈 Key Features

- ✅ Simple and fast disease detection
- ✅ VGG16-based CNN model with transfer learning
- ✅ Real-time prediction with treatment suggestions
- ✅ User-friendly and mobile-friendly UI
- ✅ High accuracy on test datasets

---

## 🧪 Testing & Results

- **Testing Methods**: Unit, Integration, System, Black Box, White Box
- **Performance**: High-speed response, low latency
- **User Feedback**: Positive reviews from real users (farmers & researchers)

---

## 🧑‍💻 Developed By

- **Gulrez Mansuri**
- Lokesh Patil
- Nilesh Beldar
- Madhusudan Badgujar

**Guide**: Prof. Dr. S. R. Suralkar  
**College**: SSBT’s College of Engineering and Technology  
**Year**: 2024–2025

---

## 📚 References

- [Frontiers in Plant Science](https://www.frontiersin.org/articles/10.3389/fpls.2016.01419/full)
- [Hindawi: Plant Leaf Classification](https://www.hindawi.com/journals/cin/2016/3289801/)

---

## 📬 License

This project is developed for academic and research purposes. Please contact for reuse or contributions.

---

## ⭐ Show your Support

If you like this project, consider giving it a ⭐ on GitHub and sharing it!

---
