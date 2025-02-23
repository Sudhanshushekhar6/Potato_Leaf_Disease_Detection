# 🍀 Potato Leaf Disease Detection

## 📌 Project Overview
The **Potato Leaf Disease Detection System** leverages **deep learning** and **image processing** to accurately identify various potato leaf diseases. This system provides farmers with actionable insights to enhance crop health and productivity.

## 🎯 Key Features
- 🔍 **AI-Powered Image Classification** using CNNs.
- 📷 **Advanced Image Preprocessing** (noise reduction, resizing, color correction).
- 📊 **Performance Metrics & Visualization** for model evaluation.
- 🌍 **User-Friendly Web Interface with Streamlit**.
- ☁ **Cloud-Enabled Deployment** for real-time disease detection.

## 🚀 Project Objectives
- Develop a robust machine learning model for disease classification.
- Ensure high detection accuracy through deep learning optimizations.
- Deploy a scalable and accessible solution for agricultural use.

## 🏗️ Technology Stack
### **Programming Languages & Frameworks**
- **Python 3.8+** (Core development)
- **TensorFlow / Keras** (Deep learning model)
- **OpenCV & PIL** (Image processing)
- **Streamlit** (Web application framework)

### **Key Libraries Used**
- `numpy`, `pandas` (Data manipulation)
- `matplotlib`, `seaborn` (Visualization tools)
- `scikit-learn` (Model evaluation & metrics)
- `streamlit` (Interactive UI for real-time predictions)

## 🏗️ System Workflow
```
+--------------------+
|  Image Input      |
+--------------------+
         ↓
+--------------------+
|  Preprocessing   |
+--------------------+
         ↓
+--------------------+
|  Deep Learning   |
+--------------------+
         ↓
+--------------------+
|  Disease Output  |
+--------------------+
```

## 🛠️ Installation & Setup
### **Prerequisites**
- Python 3.8+
- Jupyter Notebook / Google Colab
- Install dependencies using:
  ```bash
  pip install -r requirements.txt
  ```

### **Running the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/sudhanshushekhar6/potato-leaf-disease-detection.git
   ```
2. Navigate to the project folder:
   ```bash
   cd potato-leaf-disease-detection
   ```
3. Train the model (if not pre-trained):
   ```bash
   python train.py
   ```
4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## 📌 Dataset Information
The model is trained on the **PlantVillage Dataset**, which contains labeled images of potato leaves categorized as:
- ✅ Healthy
- ❌ Early Blight
- ❌ Late Blight

## 📊 Performance Metrics
| Metric      | Value  |
|------------|--------|
| Accuracy   | 92.5%  |
| Precision  | 91.8%  |
| Recall     | 93.2%  |

## 🔮 Future Enhancements
- 🌱 Integration with **IoT-based sensors** for real-time monitoring.
- 📱 Deploying a **mobile-friendly version using Streamlit Cloud**.
- 🌾 Extending the model to **detect multiple crop diseases**.

## 🤝 Contributing Guidelines
Contributions are encouraged! Follow these steps:
1. Fork the repository.
2. Create a feature branch (`feature-xyz`).
3. Commit your changes.
4. Push and submit a PR for review.

## 📜 License
This project is **open-source** under the MIT License.

---
🚀 **Developed with ❤️ to Empower Agriculture with AI!**
