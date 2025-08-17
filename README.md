# 🧠 Multiple Disease Prediction System  

A **Flask-based web application** that predicts the likelihood of **Diabetes, Heart Disease, and Parkinson’s Disease** using **Machine Learning models**.  
This project combines **ML algorithms** with a **user-friendly web interface**, making early health screening more **accessible, scalable, and impactful**.  

---

## 🚀 Features
- 🔮 **Real-time Predictions** for:
  - Diabetes  
  - Heart Disease  
  - Parkinson’s Disease  
- 🌐 **Flask Web App** with an intuitive interface  
- ⚡ **Pre-trained ML Models** (Pickle Integration)  
- 📊 Displays **dataset insights** and statistics  
- 🎨 Simple, responsive **HTML + CSS UI**  

---

## 📖 Motivation
Chronic diseases such as **Diabetes, Parkinson’s, and Heart Disease** affect millions globally, and **early detection is key** to effective management.  
However, diagnostic tools are often **costly, limited, and inaccessible** in many regions.  
This project bridges that gap by combining **ML models with web technologies**, offering a **low-cost, scalable, and easy-to-use prediction system**.  

---

## 🏗️ System Architecture
The project follows the **Model-View-Controller (MVC)** pattern for modularity and maintainability.  

- **Model** → Pre-trained ML models (`diabetes.pkl`, `heart.pkl`, `parkinsons.pkl`)  
- **View** → Disease-specific HTML forms (`home.html`, `diabetes.html`, etc.)  
- **Controller** → Flask routes (`app.py`) handling prediction logic  

---

## ⚙️ Tech Stack
- **Frontend** → HTML, CSS  
- **Backend** → Flask (Python)  
- **Machine Learning** →  
  - Logistic Regression (Heart Disease)  
  - Support Vector Machine (Diabetes & Parkinson’s)  
- **Libraries** → NumPy, Pandas, Scikit-learn, Pickle  

---


---

## 🖥️ How It Works
1. User navigates to the **disease page** (Diabetes / Heart / Parkinson’s).  
2. Fills out the **form** with health parameters.  
3. Flask app processes input → Sends to **ML model**.  
4. Model predicts (positive/negative).  
5. Result displayed on the web page.  

---

## 📊 Datasets Used
- **Diabetes Dataset** → `diabetes.csv`  
- **Heart Disease Dataset** → `heart.csv`  
- **Parkinson’s Disease Dataset** → `ParkinsonsDisease.csv`  

---

## 🌟 Future Enhancements
- Integration with **Electronic Health Records (EHR)**  
- Support for **more diseases**  
- Advanced ML models (Random Forest, XGBoost, Neural Networks)  
- Deployment on **cloud platforms** (Heroku, AWS, GCP)  
- Interactive **data visualization dashboards**  

---

## 🙌 Acknowledgements
- **Scikit-learn** for ML models  
- **Flask** for web framework  
- Datasets from **Kaggle / UCI Machine Learning Repository**  

---

## 📸 Screenshots
👉 [Click here to view Screenshots](Results.png)  
 


