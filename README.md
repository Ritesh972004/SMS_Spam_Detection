📱 SMS Fraud Detection System

A system designed to detect fraudulent SMS messages using machine learning techniques, ensuring enhanced security and protection for users.

🔗 GitHub Repository: SMS Fraud Detection System

🚀 Features
🔍 Detects spam and fraudulent messages using machine learning algorithms.
📊 Real-time detection with accuracy analysis.
💾 Utilizes a dataset of SMS messages to train the model.
🧠 Machine learning model built using Python's scikit-learn library.
🛠️ Implements both classification (spam/not spam) and anomaly detection.

🌐 Technology Stack

Python: scikit-learn for model training and evaluation

Flask: for deploying the detection system as an API

Jupyter Notebook: for data preprocessing and training model

Dataset: Public SMS spam dataset for training

🛠️ Setup & Usage

1️⃣ Prerequisites

Python (>= 3.6)

Install pip (if not installed)

Install virtual environment (optional but recommended)

2️⃣ Clone the Repository

git clone https://github.com/Ritesh972004/SMS_Spam_Detection.git
cd SMS_Spam_Detection


3️⃣ Install Dependencies
Install the required Python libraries by running:

pip install -r requirements.txt


4️⃣ Running the System
To run the machine learning model training script:

python train_model.py


To run the detection system (Flask API):

python app.py


➡️ API Runs at: http://localhost:5000

📌 API Endpoints

POST /detect
Detects if the given SMS message is spam or not.

Request body:

{ "message": "Your bank account has been compromised. Click here..." }


Response:

{ "result": "spam" }

✅ Test Cases

✅ Successfully detect spam SMS messages.
❌ Fail detection on non-spam (ham) messages.
❌ Handle edge cases such as malformed input.

🤝 Contributing

Want to improve this project? Follow these steps:

Fork the repository.

Clone it locally.

git clone https://github.com/Ritesh972004/SMS_Spam_Detection.git


Create a new branch.

git checkout -b feature-branch


Make your changes & commit.

git commit -m "Added new feature"


Push changes.

git push origin feature-branch


Open a Pull Request on GitHub.

🔥 Star this repo ⭐ if you like this project! 🚀
