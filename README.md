# 💳 **Credit Card Fraud Detection Using Deep Learning** 🛡️

## 🌟 **Overview**
Credit card fraud poses significant challenges to financial institutions and consumers. This project employs a **Long Short-Term Memory (LSTM) neural network** to detect fraudulent transactions, achieving an impressive **99.7% accuracy**. By addressing class imbalance with **Synthetic Minority Over-sampling Technique (SMOTE)** and leveraging **Principal Component Analysis (PCA)** for feature engineering, the model ensures robust and reliable fraud detection.

## 📊 **Dataset**
- **Source:** [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Transactions:** 284,807
- **Fraudulent Cases:** 492 (highly imbalanced)
- **Features:**
  - `V1` to `V28`: PCA-transformed features
  - `Time`: Seconds elapsed between this transaction and the first transaction
  - `Amount`: Transaction amount
  - `Class`: Target variable (0 = Legitimate, 1 = Fraudulent)

## 🛠️ **Technologies Used**
- **Programming Language:** Python
- **Libraries:** TensorFlow, Keras, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Machine Learning Techniques:**
  - **LSTM Neural Network:** Captures temporal dependencies in transaction data
  - **SMOTE:** Addresses class imbalance by oversampling the minority class
  - **PCA:** Reduces dimensionality and noise in the dataset

## 🔄 **Project Workflow**
1. **Data Preprocessing:**
   - Handle missing values (if any)
   - Normalize features (`StandardScaler`) to ensure consistent scaling
   - Apply **PCA** to transform features and reduce dimensionality

2. **Handling Class Imbalance:**
   - Utilize **SMOTE** to oversample fraudulent transactions, balancing the dataset

3. **Model Development:**
   - Construct an **LSTM-based neural network** to model sequential transaction data
   - Compile the model with appropriate loss functions and optimizers

4. **Model Training & Evaluation:**
   - Train the LSTM model on the balanced dataset
   - Evaluate performance using metrics: **Accuracy, Precision, Recall, F1-Score, ROC-AUC Curve**

5. **Performance Metrics:**
   - Achieved **99.7% accuracy**
   - High **Precision** and **Recall** indicating effective fraud detection
   - **ROC-AUC Score:** 0.998, demonstrating excellent model performance

## 🚀 **How to Run the Project**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/16sumanshiroy/CARD-FRAUD-DETECTION.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd CARD-FRAUD-DETECTION
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook CREDIT_CARD_FRAUD_DETECTION.ipynb
   ```

## 📈 **Results & Insights**
- The **LSTM model** effectively captures temporal patterns in transaction data, leading to high accuracy
- **SMOTE** successfully mitigates class imbalance, enhancing the model's ability to detect fraud
- **PCA** reduces noise, improving model performance and training efficiency
![download-1](https://github.com/user-attachments/assets/32671bd0-e8b3-482a-8366-7e32e73ce75e)


## 🌐 **Deployment**
- Deploy the trained model using **Flask** to create a RESTful API for real-time fraud detection
- Integrate the API into existing financial transaction systems for continuous monitoring

## 🔮 **Future Improvements**
- Explore **Convolutional Neural Networks (CNNs)** for feature extraction
- Implement **Ensemble Learning** techniques to combine multiple models for improved accuracy
- Develop a **real-time streaming pipeline** using tools like **Apache Kafka** for immediate fraud detection
- Incorporate additional features such as **geolocation data** and **transaction metadata** to enhance model robustness

## 🤝 **Contributions**
Contributions are welcome! Feel free to **fork** this repository, create **feature branches**, and submit **pull requests**. Any suggestions or issues can be reported in the **Issues** section.

## 📜 **License**
This project is licensed under the **MIT License**.

---

**📬 Connect with me:**
- **Email:** 16sumanshiroy@gmail.com
- **LinkedIn:** [Sumanshi Roy](https://linkedin.com/in/sumanshi-roy-435229230)
- **GitHub:** [16sumanshiroy](https://github.com/16sumanshiroy)

---

**🚀 Happy Coding!** 😊

