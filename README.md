📌 ML-Based CRUD Application Using Flask (No Database)

A simple Machine Learning powered CRUD web application built using Flask, HTML, CSS, and JavaScript.
This project performs Create, Read, Update, Delete (CRUD) operations without using any database by storing data in a JSON file and using a basic ML model for prediction.

🚀 Features
➕ Add new student records (Create)
📄 View all student records (Read)
✏️ Update existing student records (Update)
❌ Delete student records (Delete)
🤖 Machine Learning prediction (Pass/Fail)
💾 No database used (JSON file storage)
🌐 Simple and clean web UI
🧠 Machine Learning Concept

A simple Logistic Regression model is used to predict student performance based on:

Marks
Attendance
Output:
Pass
Fail
🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Flask (Python)
ML: scikit-learn
Data Storage: JSON file
📁 Project Structure
ml-crud-project/
│
├── app.py                # Flask backend API
├── model.py              # ML model logic
├── data.json             # JSON storage file
├── requirements.txt      # Dependencies
│
├── templates/
│   └── index.html        # Frontend UI
│
├── static/
│   ├── style.css         # Styling
│   └── script.js         # CRUD operations (JS)
│
└── README.md
⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/ml-crud-project.git
cd ml-crud-project
2. Create virtual environment (optional)
python -m venv venv
venv\Scripts\activate   # Windows
3. Install dependencies
pip install -r requirements.txt
▶️ Run the Project
python app.py

Then open in browser:

http://127.0.0.1:5000
📡 API Endpoints
Method	Endpoint	Description
GET	/students	Get all students
POST	/students	Add new student
PUT	/students/<index>	Update student
DELETE	/students/<index>	Delete student
📌 Example Input
{
  "name": "John",
  "marks": 85,
  "attendance": 1
}
Output:
Pass
🎯 Learning Outcomes
Flask API development
CRUD operations without database
Frontend + backend integration
Basic Machine Learning integration
JSON-based data handling
📸 UI Preview

(You can add screenshots here later)

![UI Screenshot](static/screenshot.png)
🔮 Future Improvements
Add SQLite / MongoDB support
Improve ML accuracy with real dataset
Add authentication system
Add charts & analytics dashboard
Deploy on cloud (Render / Heroku)
