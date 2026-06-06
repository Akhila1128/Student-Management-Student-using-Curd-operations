Gender Detection using Machine Learning & Flask
📌 Overview

This project is a web-based Gender Detection system built using Machine Learning and Flask.
It predicts the gender (Male/Female) based on a given name using a trained classification model.

The system uses a simple dataset of names and applies Natural Language Processing techniques to convert text into numerical features for prediction.

🚀 Features
Predicts gender from user-input name
Machine Learning-based classification model
Web interface built with Flask
Lightweight and fast prediction
CSV-based training dataset
Simple and interactive UI
🛠️ Tech Stack
Python
Flask
Pandas
Scikit-learn
Joblib
HTML5
CSS3
📁 Project Structure
Gender-Detection-Project/
│
├── app.py                  # Flask application
├── train_model.py          # Model training script
├── gender_dataset.csv      # Dataset file
├── model.pkl               # Trained ML model
├── vectorizer.pkl          # Feature extractor
├── requirements.txt        # Dependencies
│
├── templates/
│   └── index.html          # Frontend UI
│
├── static/
│   └── style.css           # Styling file
│
└── README.md               # Project documentation
📊 Dataset Description

The dataset contains labeled names with corresponding gender values.

ID	Name	Gender
1	KANOJ	MALE
2	SNEHA	FEMALE
3	RAHUL	MALE
4	PRIYA	FEMALE
5	ARJUN	MALE
6	DIVYA	FEMALE
7	VIKRAM	MALE
8	POOJA	FEMALE
9	KARTHIK	MALE
10	ANJALI	FEMALE
⚙️ Installation Guide
1. Clone Repository
git clone https://github.com/your-username/gender-detection-project.git
cd gender-detection-project
2. Create Virtual Environment (Optional)
python -m venv venv
venv\Scripts\activate   # Windows
3. Install Dependencies
pip install -r requirements.txt
🧠 Model Training

Train the machine learning model using:

python train_model.py

This will generate:

model.pkl
vectorizer.pkl
▶️ Run Application

Start the Flask server:

python app.py

Open in browser:

http://127.0.0.1:5000
🔍 How It Works
User enters a name
Name is converted into numerical features using CountVectorizer
Trained Naive Bayes model predicts gender
Result is displayed on the web interface
📌 Algorithm Used
Multinomial Naive Bayes Classification
📈 Example Output
Input	Output
Rahul	MALE
Sneha	FEMALE
Arjun	MALE
Pooja	FEMALE
🚀 Future Enhancements
Increase dataset size for better accuracy
Improve UI/UX design
Deploy on cloud platforms (Render / AWS / Heroku)
Add real-time API endpoint
Integrate deep learning model


📜 License

This project is licensed for educational and academic use only.
