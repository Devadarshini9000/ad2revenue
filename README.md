# 📈 ad2revenue – Advertising Budget-Based Sales Predictor

**ad2revenue** is a machine learning-powered web application that predicts **product sales** based on your advertising budget and preferred ad platforms like **TV**, **Radio**, and **Newspaper**. It helps businesses strategically allocate their marketing spend to get the best ROI.

---

## 🚀 Features

- 🧠 Trained using a **Linear Regression model**
- 📊 Predicts sales from advertising spend across various media
- 🖥️ Interactive **Streamlit dashboard** for easy use
- ⚙️ Scalable model ready for business intelligence integration

---

## 📁 Project Structure
├── preprocessed_advertising.csv # Cleaned dataset
├── sales_train.py # Script to train the ML model
├── sales_test.py # Streamlit app for prediction
├── sales_model.pkl # Trained model file
├── scaler.pkl # Scaler used for input normalization


---

## 🛠 Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- Joblib
- Streamlit

---

## 🧪 How It Works

1. **Training (`sales_train.py`)**
   - Reads the advertising dataset
   - Splits into features: TV, Radio, Newspaper
   - Trains a **Linear Regression** model
   - Saves the model as `sales_model.pkl`

2. **Prediction (`sales_test.py`)**
   - Loads trained model and scaler
   - Accepts total ad budget and platform strategy (e.g., TV + Radio)
   - Distributes budget accordingly, scales input, and predicts sales
   - Displays predicted sales via Streamlit UI

---

## 💻 How to Run the App

### 🔹 1. Clone the Repo

```bash
git clone https://github.com/yourusername/ad2revenue.git
cd ad2revenue

### **2.Install Requirements**
pip install streamlit pandas scikit-learn joblib numpy

### **3. Train the Model** (Optional if sales_model.pkl already exists)
bash
python sales_train.py

### **4. Launch the Dashboard**
streamlit run sales_test.py

🧠 **Use Cases**
📊 Marketing campaign planning
🧾 Budget forecasting
💰 ROI estimation for ad spend
📍 Strategy optimization across platforms

👩‍💻 Author
Devadarshini P
🔗 LinkedIn
💻 GitHub

“Predict smart. Spend smart. Grow fast.” – ad2revenue
<img width="1906" height="893" alt="image" src="https://github.com/user-attachments/assets/1fa8c375-7f83-4446-b2c3-667c6669e7b6" />




