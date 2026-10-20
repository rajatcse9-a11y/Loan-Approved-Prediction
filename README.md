🏦 Loan Approval Prediction using Deep Learning

An AI-powered Loan Approval Prediction application built using TensorFlow, Scikit-learn, and Streamlit. The application analyzes applicant financial details and predicts the likelihood of loan approval using a trained deep learning model.

🚀 Features

- Deep Learning-based loan prediction
- Interactive and user-friendly Streamlit interface
- Applicant financial information input
- Approval and rejection probability visualization
- Data preprocessing using a saved preprocessing pipeline
- Real-time predictions
- Model inference using a trained Keras model

🛠️ Tech Stack

- Programming Language: Python
- Deep Learning: TensorFlow / Keras
- Machine Learning: Scikit-learn
- Data Processing: Pandas, NumPy
- Frontend: Streamlit
- Model Serialization: Pickle
- Version Control: Git and GitHub

📂 Project Structure

Loan-Approval-Prediction/
│
├── loan_approval_model.keras
├── preprocessor.pkl
├── requirements.txt
└── README.md

📊 Dataset Features

The model uses applicant information such as:

- Number of dependents
- Education
- Self-employment status
- Annual income
- Loan amount
- Loan term
- CIBIL score
- Residential asset value
- Commercial asset value
- Luxury asset value
- Bank asset value

⚙️ Installation and Setup

1. Clone the Repository

git clone YOUR_GITHUB_REPOSITORY_URL
cd Loan-Approval-Prediction

Replace "YOUR_GITHUB_REPOSITORY_URL" with your actual GitHub repository URL.

2. Create a Virtual Environment (Optional)

python -m venv venv

Activate it on Windows:

venv\Scripts\activate

3. Install Dependencies

pip install -r requirements.txt

4. Run the Application

streamlit run app.py

The application will open in your browser.

🧠 Model Workflow

1. Collect applicant information through the Streamlit interface.
2. Convert the input into a structured DataFrame.
3. Apply the saved preprocessing pipeline.
4. Pass the transformed features to the trained neural network.
5. Display the model's prediction and probability estimates.

📈 Prediction Output

The application displays:

- Predicted loan status
- Approval probability
- Rejection probability
- Applicant information used for prediction

Prediction probabilities depend on the model's output layer and label encoding.

🔮 Future Improvements

- Deploy the application on Streamlit Community Cloud.
- Add model evaluation metrics and a confusion matrix.
- Improve input validation and error handling.
- Add explainable AI techniques for understanding predictions.
- Integrate a FastAPI backend for a separate frontend and inference service.

👨‍💻 Author

Rajat Maurya

- GitHub: "rajatcse9-a11y" (https://github.com/rajatcse9-a11y)
- LinkedIn: "Rajat Maurya" (https://www.linkedin.com/in/rajat-maurya-6a6b72354/)

⚠️ Disclaimer

This project is developed for educational and demonstration purposes. Predictions are model estimates and should not be treated as actual financial or lending decisions.

---

⭐ If you find this project useful, consider giving the repository a star.