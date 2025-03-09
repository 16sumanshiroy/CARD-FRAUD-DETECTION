# Credit Card Fraud Detection  

## 📌 Project Overview  
This project focuses on **credit card fraud detection** using **Artificial Intelligence (AI) and Deep Learning** techniques. It employs **Long Short-Term Memory (LSTM)** networks and **Synthetic Minority Over-sampling Technique (SMOTE)** to improve fraud detection accuracy by handling class imbalance.  

## 📂 Project Structure  
├── data/ # Dataset files │ ├── creditcard.csv # Original dataset │ ├── preprocessed_data.csv # Cleaned and transformed dataset │ ├── models/ # Trained models │ ├── lstm_fraud_model.h5 # LSTM model file │ ├── scaler.pkl # Scaler for data normalization │ ├── notebooks/ # Jupyter Notebooks for experimentation │ ├── data_preprocessing.ipynb │ ├── model_training.ipynb │ ├── evaluation.ipynb │ ├── results/ # Visualization and evaluation results │ ├── accuracy_plot.png │ ├── confusion_matrix.png │ ├── correlation_heatmap.png │ ├── src/ # Source code files │ ├── data_processing.py # Data cleaning and feature engineering │ ├── model.py # LSTM model implementation │ ├── evaluation.py # Model performance evaluation │ ├── main.py # Main script to run the project │ ├── requirements.txt # Python dependencies ├── README.md # Project documentation (this file)

markdown
Copy
Edit

## 📊 Dataset  
The dataset used is the **Credit Card Fraud Detection Dataset** from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).  
- Contains **284,807** transactions, with only **492 fraudulent cases** (highly imbalanced).  
- Features include **V1-V28 (PCA transformed features)**, **Amount**, **Time**, and **Class (0: Legitimate, 1: Fraudulent)**.  

## 🔥 Key Features  
✅ **Data Preprocessing**: Feature scaling, handling missing values, and transformation.  
✅ **Imbalance Handling**: **SMOTE** is used to balance fraud and legitimate transactions.  
✅ **Deep Learning Model**: **LSTM-based neural network** trained for fraud detection.  
✅ **Performance Metrics**: Accuracy, Precision, Recall, F1-score, ROC-AUC curve.  

## 🛠 Installation & Setup  
1️⃣ Clone the repository:  
```sh
git clone https://github.com/yourusername/ai-deep-learning-fraud-detection.git
cd ai-deep-learning-fraud-detection
2️⃣ Install dependencies:

sh
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the project:

sh
Copy
Edit
python src/main.py

📈 Results
LSTM achieves high accuracy (~99.9%) while maintaining good recall on fraud cases.
SMOTE effectively balances class distribution, improving fraud detection performance.
Feature correlation heatmap visualizes relationships between variables.

![download-1](https://github.com/user-attachments/assets/63cf56cb-a981-4d4f-9001-f89b4d5292df)




🤖 Future Improvements
Experiment with Transformer-based models for enhanced fraud detection.
Combine LSTM with anomaly detection techniques for hybrid detection.
Deploy the model using Flask or FastAPI for real-time fraud detection.
📄 License
This project is open-source under the MIT License.

📌 Connect with me:
📧 Email: 16sumanshiroy@gmail.com
🔗 LinkedIn: Sumanshi Roy
🐍 GitHub: 16sumanshiroy

🚀 Happy Coding!

