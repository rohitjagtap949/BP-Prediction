
# 🩺 Predictive Pulse: Blood Pressure Stage Prediction

## 📘 Project Overview
This machine learning project predicts the stage of blood pressure (e.g., Normal, Pre-hypertension, Stage-1, Stage-2) based on patient data.

The project involves:
- Data preprocessing and visualization
- Label encoding of categorical values
- Model building and evaluation (Random Forest, Decision Tree, etc.)
- Web application using Flask (optional)

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `BP_Prediction.ipynb` | Jupyter notebook with full data analysis and model training |
| `model.pkl` | Saved trained model |
| `app.py` | Flask backend script for web interface |
| `templates/index.html` | HTML frontend form |
| `patient_data.csv` | Dataset used for training and prediction |
| `README.md` | This file |

---

## 🧪 How to Use

### ▶️ Option 1: Run Notebook
1. Open `BP_Prediction.ipynb` in Jupyter or VS Code
2. Run all cells to see model training, results, and plots

### ▶️ Option 2: Run the Web App
1. Run the training script (if `.pkl` doesn't exist):
    ```bash
    python train_model.py
    ```
2. Then start the Flask app:
    ```bash
    python app.py
    ```
3. Open browser and visit:
    ```
    http://127.0.0.1:5000
    ```

---

## 🧠 Algorithms Used
- Random Forest
- Decision Tree
- Logistic Regression
- Naive Bayes
- AdaBoost

---

## 📊 Libraries Used
- Python, Pandas, NumPy
- Seaborn, Matplotlib
- scikit-learn
- Flask (for web app)

---

## 📌 Notes
- Make sure all files are in the correct folders
- Encoded values must match training (e.g., 0 for Female, 1 for Male)

---

## 🙋‍♀️ Author
Mounika Vipparty 
Rohit Jagtap
Rushikesh Hapse 
Final Year Student, SmartBridge Capstone Project

