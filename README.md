# 🐄 Livestock Disease Prediction

A Flask-based machine learning web application that predicts livestock diseases using symptoms like age, temperature, and health indicators. This tool aims to help farmers and veterinarians detect livestock diseases early through a simple web interface.

---

## 🔍 Overview

This project uses a **Random Forest Classifier** to identify livestock diseases based on:

- Animal Type  
- Age  
- Temperature  
- 3 Key Symptoms  

It is built as a lightweight and user-friendly Flask web app.

---

## 📊 Dataset

- **Source**: [Kaggle - Livestock Symptoms and Diseases](https://www.kaggle.com/datasets/researcher1548/livestock-symptoms-and-diseases)  
- The dataset contains multiple animal types, associated symptoms, and labeled diseases.

---

## 🧠 Model Details

- **Algorithm**: Random Forest Classifier  
- **Training Data**: Cleaned and preprocessed symptom-based data  
- **Input Features**:
  - Animal Type (e.g., Cow, Buffalo, Goat)
  - Age (in years)
  - Body Temperature (°C)
  - Symptom 1
  - Symptom 2
  - Symptom 3
- **Output**: Predicted Disease (e.g., Mastitis, Foot-and-Mouth, Anthrax)

---

## 💻 Tech Stack

- Python  
- Flask  
- Scikit-learn  
- Pandas & NumPy  
- HTML/CSS  
- Bootstrap (for responsive UI)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/vir123-devf/Disease_Prediction.git
cd Disease_Prediction/Syntom_based_Disease_Prediction
````

### 2. Create and Activate Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate        # For Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
flask --app application.py run
```

Visit the app in your browser at: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

---

## 🌐 Application Flow

1. User selects **Animal Type**, enters **Age** and **Temperature**.
2. Chooses 3 symptoms from dropdown lists.
3. Clicks **Predict**.
4. Model predicts the disease and displays it instantly.

---

## 📸 Screenshots

*Add screenshots of your web interface here.*

---

## 📌 Project Structure

```
Syntom_based_Disease_Prediction/
│
├── application.py            # Flask app
├── model.pkl                 # Trained Random Forest model
├── templates/
│   └── index.html            # Frontend form
├── static/
│   └── style.css             # CSS styling
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

---

## 🔮 Future Enhancements

* ✅ Add treatment suggestions based on diagnosis
* 🌍 Multilingual support for rural regions
* 🔊 Voice-based input for low-literacy users
* ☁️ Deploy on Render / Heroku
* 📈 Add dashboard for analytics and tracking

---

## 🤝 Author

* **Virendra Badgotya** – [@vir123-devf](https://github.com/vir123-devf)

---

## 📜 License

This project is for educational and prototype purposes. Always consult a certified veterinarian before taking action based on model output.

---
