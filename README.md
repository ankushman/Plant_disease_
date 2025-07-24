# 🌱 Plant Disease Prediction App

This Streamlit web app predicts whether a plant is **diseased** or **healthy** based on environmental conditions such as temperature, humidity, rainfall, and soil pH.

---

## 🚀 Live Demo

👉 [Click here to use the deployed app]
(https://plantdisease-ekpmzc7zuvzapukowmwhne.streamlit.app/)

---

## 🧠 Model Description

The model is trained using environmental features to classify plant health.  
It uses a machine learning algorithm (e.g., RandomForest, DecisionTree, etc.) and is saved as a `plant_disease_model.pkl` file.

### Input Features:
- 🌡️ Temperature (°C)
- 💧 Humidity (%)
- 🌧️ Rainfall (mm)
- 🌱 Soil pH

---

## 📸 Note

This project **does not support image-based plant disease detection**.  
If you're looking for a leaf-image classifier, that would require:
- A trained CNN model
- Image preprocessing (resize, normalize, etc.)
- `st.file_uploader()` in the app

---

## 🛠️ Installation (Local Setup)

```bash
# Clone the repo
git clone https://github.com/Saptak20/Plant_Disease_Prediction.git
cd Plant_Disease_Prediction

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
