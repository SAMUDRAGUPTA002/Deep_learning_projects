# 🏥 Heart Disease Prediction Using Deep Learning  

---

## 📌 Overview  
This project implements **Heart Disease Prediction** using **Deep Learning models** like **ANN, CNN, LSTM, and Autoencoders**. The goal is to predict whether a patient has heart disease based on medical indicators.  

---

## 🚀 Technologies Used  
- **Python** 🐍  
- **TensorFlow/Keras** – Deep Learning framework  
- **Scikit-learn** – Data preprocessing & evaluation  
- **Pandas & NumPy** – Data handling  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter Notebook** – Model development  

---

## 📂 Dataset  
The dataset contains **patient health records** with key medical indicators:  
✅ **Features:**  
   - `age` – Patient's age  
   - `sex` – Gender (Male/Female)  
   - `cp` – Chest pain type  
   - `trestbps` – Resting blood pressure  
   - `chol` – Cholesterol level  
   - `fbs` – Fasting blood sugar  
   - `thalach` – Maximum heart rate achieved  
   - `oldpeak` – ST depression induced by exercise  
   - And other medical parameters  

✅ **Target Variable:**  
   - `num` – **1 (Heart Disease), 0 (No Heart Disease)**  

---

## ⚙️ Installation & Setup  
#### 1️⃣ Clone the repository  
```bash
git clone https://github.com/YourRepo/Heart-Disease-Prediction.git  
cd Heart-Disease-Prediction  
```
#### 2️⃣ Install dependencies  
```bash
pip install -r requirements.txt  
```
#### 3️⃣ Run the model  
```bash
python heart_disease_prediction.py  
```

---

## 📊 Exploratory Data Analysis (EDA)  
🔹 **Missing value analysis**  
🔹 **Correlation heatmap to identify key risk factors**  
🔹 **Box plots & histograms for feature distribution**  
🔹 **Chi-Square & T-tests to find significant predictors**  

---

## 🤖 Model Training & Evaluation  
### **🏥 Deep Learning Models**
🔹 **Preprocessing:** Standardizing features for better convergence  
🔹 **Models Used:**  
   ✅ **Artificial Neural Network (ANN)**  
   ✅ **Convolutional Neural Network (CNN)**  
   ✅ **Long Short-Term Memory (LSTM)**  
   ✅ **Autoencoder (for anomaly detection)**  

🔹 **Evaluation Metrics:**  
✅ **ANN Accuracy:** **72.28%**  
✅ **CNN Accuracy:** **81.52%**  
✅ **LSTM Accuracy:** **83.15%**  
✅ **Autoencoder Loss:** **7220.4404**  

---

## 🔥 Results  
📌 The **LSTM model** performed the best with **83.15% accuracy**, making it the most effective for heart disease prediction.  
📌 **CNN achieved 81.52% accuracy**, slightly lower than LSTM but still robust.  
📌 **ANN had the lowest accuracy (72.28%)**, indicating room for improvement.  
📌 **Autoencoder showed a high loss**, meaning it may not be the best standalone model for classification.  

---

## 💡 Future Enhancements  
🚀 Improve accuracy using **Hyperparameter Tuning**  
🚀 Experiment with **Transformer models for sequential health data**  
🚀 Deploy as a **Web App using Flask or FastAPI**  

---

## 📜 License  
This project is licensed under the **MIT License**.  
