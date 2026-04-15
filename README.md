# FetalAI-Using-Machine-Learning

🏥 Fetal Health Classification Web Application

A modern, professional web application that uses Machine Learning to predict fetal health based on cardiotocogram (CTG) data.

🔗 GitHub Repository:
👉 https://github.com/rounak071203/FetalAI-Using-Machine-Learning

📧 Contact:
👉 rounakgajbar09@gmail.com

🌟 Features
✨ Multi-Page Web App
🏠 Home page with project overview
🔍 Prediction page with 21 CTG inputs
📞 Contact page
🤖 AI Capabilities
Real-time fetal health prediction
Confidence score output
95%+ accuracy (Random Forest model)
REST API support
Input validation & error handling
Responsive UI (mobile-friendly)
📦 Project Structure
fetal-health-classification/
│
├── app.py
├── requirements.txt
├── README.md
├── dataset/
│   └── fetal_health.csv
├── templates/
│   ├── home.html
│   ├── index.html
│   ├── output.html
│   ├── contact.html
│   └── inspect.html
└── optimized_fetal_health_model.pkl
🚀 Getting Started
🔧 Prerequisites
Python 3.7+
Git
pip
📥 Clone Repository
git clone https://github.com/rounak071203/FetalAI-Using-Machine-Learning.git
cd FetalAI-Using-Machine-Learning
🧪 Create Virtual Environment

Windows:

python -m venv venv
venv\Scripts\activate

macOS/Linux:

python3 -m venv venv
source venv/bin/activate
📦 Install Dependencies
pip install --upgrade pip
pip install -r requirements.txt
▶️ Run Application
python app.py

Open in browser:

http://127.0.0.1:5000
🧠 How It Works

The model predicts fetal health into 3 categories:

Class	Status	Meaning
1	✅ Normal	Healthy condition
2	⚠️ Suspect	Needs monitoring
3	❌ Pathological	Immediate attention required
🔌 API Endpoint
POST /api/predict

Example:

curl -X POST http://127.0.0.1:5000/api/predict \
-H "Content-Type: application/json" \
-d '{ "baseline value": 120.0 }'
⚙️ Tech Stack
Backend
Flask
Python
scikit-learn
pandas, numpy
Frontend
HTML5
CSS3
JavaScript
⚠️ Disclaimer
This project is for educational purposes only
Not intended for real medical diagnosis
Always consult healthcare professionals
👨‍💻 Author

Rounak Gajbar

📧 Email: rounakgajbar09@gmail.com

🔗 GitHub: https://github.com/rounak071203/FetalAI-Using-Machine-Learning

⭐ Support

If you like this project:

⭐ Star the repo
🍴 Fork it
🛠️ Contribute
🎉 Final Note

Thanks for using this project!
Happy Coding 🚀
