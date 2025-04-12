# ANN_Customer_Churn_Prediction

ANN_Customer_Churn_Prediction

Overview:
This project implements an Artificial Neural Network (ANN) to predict customer churn based on various customer attributes. The model is trained using the Keras library and is designed to help businesses identify customers who are likely to leave, enabling proactive retention strategies.

Features:
- Data preprocessing including encoding categorical variables and feature scaling.
- ANN model built with Keras, trained to predict churn.
- Model evaluation using appropriate metrics.
- Deployment-ready code with saved model and encoders.

Tech Stack:
- Python
- Keras
- scikit-learn
- Pandas
- NumPy

Project Structure:
ANN_Customer_Churn_Prediction/
├── Churn_Modelling.csv           - Dataset used for training and evaluation
├── app.py                        - Script for deploying the model
├── experiments.ipynb             - Notebook containing model training and evaluation
├── prediction.ipynb              - Notebook for making predictions with the trained model
├── model.h5                      - Saved ANN model
├── label_encoder_gender.pkl      - Saved label encoder for gender
├── onehot_encoder_geo.pkl        - Saved one-hot encoder for geography
├── scaler.pkl                    - Saved scaler for feature scaling
├── requirements.txt              - Python dependencies
├── LICENSE                       - Project license
└── README.md                     - Project documentation

Installation Instructions:
1. Clone the repository:
   git clone https://github.com/shivam-kr935/ANN_Customer_Churn_Prediction.git
   cd ANN_Customer_Churn_Prediction

2. Create and activate a virtual environment:
   python -m venv venv
   On Windows: venv\Scripts\activate
   On Mac/Linux: source venv/bin/activate

3. Install dependencies:
   pip install -r requirements.txt

4. Run the application:
   python app.py

Usage:
- Use the `experiments.ipynb` notebook to understand the model training process.
- Use the `prediction.ipynb` notebook to make predictions with the trained model.
- The `app.py` script can be used to deploy the model for real-time predictions.

License:
This project is licensed under the GPL-2.0 License.

Contributing:
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

Contact:
For any inquiries or support, please contact Shivam Kumar at https://github.com/shivam-kr935.
