🎭 AI Deepfake Defense

A real-vs-fake video detector that uses AI and computer vision to detect deepfakes with **Grad-CAM visual explanations**.

---

## ✨ Features
- **Face Detection & Extraction** from videos
- **Deep Learning Model** to classify real vs fake faces
- **Grad-CAM Heatmaps** to visualize decision-making
- **Real-Time Detection** capability
- **Streamlit Web App** for user-friendly interaction
- **Data Pipeline & Logging** for reproducibility

---

## 📂 Project Structure
deepfake-detector-app/  
│  
├── deepfake_face_extractor.ipynb   → Extracts faces from videos  
├── app.ipynb                        → Streamlit app code  
├── requirements.txt                 → Python dependencies  
├── README.md                        → Project documentation  
└── sample_videos/                   → Example input videos  

---

## 🛠️ Installation & Setup

**1️⃣ Clone the Repository**  
    git clone https://github.com/harinirajendran26/deepfake-detector-app.git  
    cd deepfake-detector-app  

**2️⃣ Install Dependencies**  
    pip install -r requirements.txt  

**3️⃣ Run the App Locally**  
    streamlit run app.py  

---

## 📊 How It Works
1. **Video Input** → Upload a video (real or fake)  
2. **Face Extraction** → Frames processed & faces detected  
3. **Model Prediction** → CNN classifies each face  
4. **Explainability** → Grad-CAM heatmaps show focus areas  
5. **Output** → Classification + visual explanation  

---

## 📸 Demo
*(To be added after app is running)*

---

## 🚀 Future Improvements
- Support for **audio-based deepfake detection**  
- Expand to **multi-face detection in group videos**  
- **Deploy on cloud** for large-scale real-time usage  

---

## 🙌 Credits
- Libraries: TensorFlow, OpenCV, Streamlit, tf-keras-vis

