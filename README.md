# 📊 Sales Prediction with Hybrid Model (RandomForest + XGBoost)

Welcome to my final year machine learning project! This system predicts outlet sales using a hybrid of **RandomForest** and **XGBoost** models with a clean and interactive Gradio interface.

🎥 **Watch Demo Video:** [Click here to view on YouTube](https://youtu.be/IQveur)

## 🚀 Features

- 🤖 **Hybrid ML Model:** Combines the power of RandomForest and XGBoost
- 🧾 **Input Fields:**
  - Outlet ID
  - Establishment Year
  - Outlet_Age_Sales_Interaction
- 📊 **Real-time Prediction Output** with:
  - Predicted Sales
  - Pie Chart visualization
- 📂 **Export Options:**
  - Download results in **PDF**, **Excel (XLSX)**, or **CSV** format
- 💻 **Built with:** Python, Scikit-learn, XGBoost, Gradio, Matplotlib, Pandas, FPDF


## 📁 Project Files

- `app.py` – Main app file for Gradio interface  
- `rf_model.pkl` – Trained RandomForest model  
- `xgb_model.pkl` – Trained XGBoost model  
- `requirements.txt` – Required Python libraries  
- `README.md` – Project documentation  


## 🧪 Run It Locally

bash
pip install -r requirements.txt
python app.py
