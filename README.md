# 📉 ANN-Based Customer Churn Prediction

This project builds an **Artificial Neural Network (ANN)** model to predict whether a customer will churn (leave a service) or not, using a real-world bank customer dataset. It demonstrates how deep learning models can be used to handle classification problems in customer retention and engagement.

---

## 📌 About the Project

Customer churn is a critical business metric that can help companies retain valuable users. This project uses an ANN built with **TensorFlow and Keras** to classify customers based on their likelihood of churning.

The model was trained on various features such as credit score, geography, tenure, balance, and activity. After preprocessing and model training, it achieved high accuracy in predicting churn behavior.

---

## 🧰 Tech Stack

- **Language:** Python  
- **Libraries:** TensorFlow, Keras, Pandas, NumPy, Scikit-learn, Matplotlib  
- **Model:** Artificial Neural Network (Sequential model)  
- **Data Source:** Bank Customer Churn Dataset

---

## 📊 Features Used

- Credit Score  
- Geography  
- Gender  
- Age  
- Tenure  
- Balance  
- Number of Products  
- Has Credit Card  
- Is Active Member  
- Estimated Salary

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/shivam-kr935/ANN_Customer_Churn_Prediction.git
cd ANN_Customer_Churn_Prediction

# Install dependencies
pip install -r requirements.txt

# Run the main script (example)
python ann_churn_model.py

📋 Model Performance
Metric	Value (approx.)
Accuracy	86%
Precision	High
Recall	Balanced

Performance may vary based on random seed, tuning, and train-test split.

📁 Project Structure
bash
Copy
Edit
.
├── ann_churn_model.py        # ANN training & evaluation
├── churn_prediction_model.h5 # Saved model
├── dataset/                  # Contains Churn_Modelling.csv
├── requirements.txt
└── README.md
🧠 Model Architecture
Here’s a breakdown of the ANN model used:

Input Layer:
11 features after encoding categorical variables.

Hidden Layer 1:
6 neurons, activation = ReLU

Hidden Layer 2:
6 neurons, activation = ReLU

Output Layer:
1 neuron, activation = Sigmoid (for binary classification)

Loss Function:
Binary Crossentropy

Optimizer:
Adam

Metric:
Accuracy

👤 Author
Shivam Kumar
🔗 LinkedIn
💻 GitHub
