# Heart Disease Prediction Using Deep Learning

## 📌 Overview
This project implements heart disease prediction using multiple deep learning models, including:
- **Convolutional Neural Networks (CNN)**
- **Artificial Neural Networks (ANN)**
- **Long Short-Term Memory (LSTM)**
- **Autoencoder**

The dataset used is the **UCI Heart Disease Dataset**, which contains medical attributes that help predict heart disease risk.

## 📊 Features
- **Multiple deep learning models for comparison**
- **Data preprocessing & feature engineering**
- **Model training and evaluation**
- **Graphical performance analysis**
- **Interactive UI using Streamlit**

## 📂 Project Structure
```
│── heart_disease_uci.csv        # Dataset
│── heart_disease_dl.py          # Main deep learning script
│── streamlit.py                 # Streamlit UI for predictions
│── models/                      # Saved trained models
│── requirements.txt             # Dependencies
│── README.md                    # Project documentation
```

## 🔧 Installation
1. **Clone the repository**
   ```sh
   git clone <repository-url>
   cd heart-disease-prediction
   ```
2. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the deep learning script**
   ```sh
   python heart_disease_dl.py
   ```
4. **Launch the Streamlit UI**
   ```sh
   streamlit run streamlit.py
   ```

## 📈 Model Performance
The following models were trained and evaluated:
| Model  | Accuracy |
|--------|----------|
| ANN | 83.15% |
| CNN | 84.24% |
| LSTM | 76.09% |
| Autoencoder | 72.94 |

## 📊 Visualizations
- **Confusion Matrix**
- **Feature Importance**
- **Loss & Accuracy Curves**

## 📝 Future Improvements
- Hyperparameter tuning
- Deployment as a web application
- Integration with real-world medical data

---
### 👨‍💻 Author: Shivam

