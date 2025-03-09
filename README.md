# AI & Deep Learning Credit Card Fraud Detection  

## 📌 Overview  
This project leverages **AI and Deep Learning** techniques to detect fraudulent credit card transactions. Using an **LSTM-based neural network**, the model analyzes transaction patterns, while **SMOTE (Synthetic Minority Over-sampling Technique)** handles class imbalance to improve fraud detection accuracy. The model achieves an accuracy of **99.7%**, ensuring highly reliable fraud detection.  

## 📊 Dataset  
The dataset used is the **Credit Card Fraud Detection Dataset** from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).  
- Contains **284,807 transactions** with only **492 fraudulent cases** (highly imbalanced).  
- Features include **V1-V28 (PCA-transformed features)**, **Amount**, **Time**, and **Class (0 = Legitimate, 1 = Fraudulent)**.  

## 🛠 Technologies Used  
- **Programming Language:** Python  
- **Libraries:** TensorFlow/Keras, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Deep Learning Model:** Long Short-Term Memory (LSTM)  
- **Imbalance Handling:** SMOTE for synthetic data generation  

## 🔄 Project Workflow  
### **1️⃣ Data Preprocessing**  
✔ Handling missing values  
✔ Feature scaling & normalization  
✔ Addressing class imbalance using **SMOTE**  

### **2️⃣ Exploratory Data Analysis (EDA)**  
✔ Visualizing fraud vs legitimate transactions  
✔ Feature correlation analysis using heatmaps  

### **3️⃣ Model Training & Evaluation**  
✔ Splitting dataset into **train-test sets (80-20)**  
✔ Training an **LSTM model** for fraud detection  
✔ Evaluating performance using accuracy, precision, recall, and F1-score  

### **4️⃣ Performance Metrics**  
✔ **Accuracy:** 99.7%  
✔ **Precision:** High precision ensures minimal false positives  
✔ **Recall:** Effectively detects fraudulent cases  
✔ **ROC-AUC Score:** 0.99, indicating a highly reliable model  

## 🎯 Results  
- The **LSTM-based model achieved 99.7% accuracy** in fraud detection.  
- **SMOTE significantly improved class balance**, enhancing fraud detection recall.  
- **Feature correlation analysis helped identify key fraud indicators.**  

## 🚀 How to Run the Project  
1️⃣ **Clone the repository:**  
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git

2️⃣ **Navigate to the project directory:**

bash
Copy
Edit
cd credit-card-fraud-detection

3️⃣ **Install dependencies:**

bash
Copy
Edit
pip install -r requirements.txt

4️⃣ **Run the Jupyter Notebook or Python script:**

bash
Copy
Edit
jupyter notebook  
# or  
python fraud_detection.py

## 🔮 Future Improvements
✔ Implement Transformer-based models for better sequence learning
✔ Integrate Autoencoder-based Anomaly Detection alongside LSTM
✔ Deploy the model using Flask or FastAPI for real-time fraud detection

## 🤝 Contributions
Feel free to fork this repository, create feature branches, and submit pull requests (PRs). Any contributions, issues, or suggestions are welcome!

## 📄 License
This project is open-source under the MIT License.

## 📌 Connect with Me
📧 Email: 16sumanshiroy@gmail.com
🔗 LinkedIn: Sumanshi Roy
🐍 GitHub: 16sumanshiroy

🚀 Happy Coding! 😊
