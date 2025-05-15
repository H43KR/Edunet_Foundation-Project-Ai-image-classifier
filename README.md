# 🖼️ AI Image Classifier

An AI-powered web application that classifies uploaded images using a pre-trained deep learning model. Built with TensorFlow's MobileNetV2 and Streamlit, it provides real-time top-3 predictions for any image input.

---

## 🚀 Demo

> Upload an image and let the AI tell you what's in it!

![Screenshot]
<img width="959" alt="Screenshot 2025-05-14 214006" src="https://github.com/user-attachments/assets/5f19add6-e233-4f20-904b-7fdb1a9c8743" />


---

## 📌 Features

- 📷 Upload `.jpg` or `.png` image files.
- 🔍 View top 3 predictions with confidence percentages.
- ⚡ Fast and lightweight MobileNetV2 architecture.
- 🌐 Simple and clean UI using Streamlit.

---

## 🛠️ Technologies Used

- **Python 3**
- **TensorFlow** (Keras API)
- **MobileNetV2** (Pre-trained on ImageNet)
- **OpenCV & PIL** for image preprocessing
- **Streamlit** for building the web interface

---

## 📂 Project Structure


---

## ⚙️ Installation & Run Locally

1. **Clone the repo**
```bash
git clone https://github.com/yourusername/ai-image-classifier.git
cd ai-image-classifier

2. Install dependencies

pip install -r requirements.txt

streamlit run main.py

🧠 How It Works
Loads the MobileNetV2 model with imagenet weights.

User uploads an image (JPEG/PNG).

The image is resized to 224x224, normalized, and fed into the model.

The model returns the top-3 predicted classes and their probabilities.

Results are displayed directly in the web interface.

📸 Sample Output

🧩 Future Enhancements
Support additional models (ResNet, EfficientNet)

Add object detection features

Improve UI with enhanced results display

Create API for mobile integration

📄 License
This project is open-source and available under the MIT License.

🙌 Acknowledgements
TensorFlow Keras

Streamlit Docs

ImageNet Dataset


