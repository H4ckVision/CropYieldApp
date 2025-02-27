# 🌾 Crop Yield Prediction App  

This repository contains a **Flask-based web application** that predicts **crop yield** based on key agricultural factors, including **rainfall, soil quality, farm size, sunlight, and fertilizer usage**. The application leverages a **trained machine learning model (`Crop_Yield_model.pkl`)** and provides a simple, intuitive web interface for user input and prediction.  

## 🚀 Features  

- **📊 Input Features:**  
  - **Rainfall (mm):** Average seasonal rainfall (Range: **500 – 2000 mm**)  
  - **Soil Quality Index:** Rated on a scale of **1 (poor) to 10 (excellent)**  
  - **Farm Size (hectares):** Total cultivated land (Range: **10 – 1000 hectares**)  
  - **Sunlight (hours):** Daily average sunlight during the growing season (Range: **4 – 12 hours**)  
  - **Fertilizer (kg/hectare):** Fertilizer applied per hectare (Range: **100 – 3000 kg/hectare**)  

- **📈 Prediction Output:**  
  - Estimated **crop yield** in **tons per hectare**  

- **💻 User-Friendly Interface:**  
  - A clean, responsive **GUI** for easy input and result visualization  
  - Styled using **HTML, CSS, and Font Awesome icons**  

- **☁️ Ready for Deployment:**  
  - Can be deployed on **Render, Heroku, or any cloud platform**  

---

## 🛠 Technologies Used  

- **Backend:** Flask (Python)  
- **Frontend:** HTML, CSS, JavaScript  
- **Machine Learning:** Scikit-learn  
- **Icons & Styling:** Font Awesome  
- **Deployment:** Render, Heroku, or any cloud provider  

---

## 🌍 Live Demo  

A live version of the app is available on Render:  
👉 **[Crop Yield Prediction App](https://cropyieldapp.onrender.com)**  

---

## 📌 How to Use  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/H4ckVision/CropYieldApp.git
cd CropYieldApp
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the App Locally  
```bash
python app.py
```
📌 Open your browser and visit **`http://127.0.0.1:5000/`**.  

### 4️⃣ Deploy on Render (or Heroku)  
- Push the code to GitHub  
- Connect the repository to **Render/Heroku**  
- Deploy the app  

---

## 📂 Project Structure  

```
CropYieldApp/
├── app.py                # Flask application
├── requirements.txt      # Python dependencies
├── Crop_Yield_model.pkl  # Trained ML model
├── scaler.pkl            # Pre-trained StandardScaler for input normalization
├── templates/
│   └── index.html        # Frontend HTML
├── static/
│   ├── style.css         # CSS for styling
│   └── fields.jpg        # Background image
```

---

## 🤝 Contributing  

Contributions are welcome! Follow these steps:  
1. **Fork** the repository  
2. Create a **new branch** (`git checkout -b feature/NewFeature`)  
3. **Commit** your changes (`git commit -m "Add New Feature"`)  
4. **Push** to the branch (`git push origin feature/NewFeature`)  
5. **Submit a Pull Request**  

---

## 📜 License  

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

---

## 🎖️ Acknowledgments  

- **Background Image:** [Unsplash](https://unsplash.com/)  
- **Icons:** [Font Awesome](https://fontawesome.com/)  
