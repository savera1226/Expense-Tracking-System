# 💰 Expense Tracking System 🚀
**📊 Your Smart, Fast, and Efficient Expense Manager**

The **Expense Tracking System** is a modern, full-stack application designed to help individuals and businesses track expenses effortlessly. Powered by **FastAPI** (backend) and **Streamlit** (frontend), it offers a smooth, high-performance experience with real-time analytics and insights.

---

## 🔥 Features

- **Seamless Expense Tracking** – Add, edit, and delete expenses with ease.
- **Monthly & Category-Based Analytics** – Gain insights into spending habits.
- **Intuitive & Interactive UI** – Built with Streamlit for a dynamic experience.
- **Lightning-Fast API** – FastAPI ensures high-speed, scalable performance.
- **Modular & Scalable** – Designed with best practices for future enhancements.

---

## 📁 Project Structure

## 🚀 Project Structure

```plaintext
expense_tracking_system/
├── BACKEND/                 # FastAPI backend server
│   ├── __init__.py          # Package initializer
│   ├── db_helper.py         # Handles database interactions
│   ├── logging_setup.py     # Logging configuration
│   ├── my_app.log           # Log file for errors/events
│   ├── server.log           # API request logs
│   └── server.py            # Main FastAPI server
├── FRONTEND/                # Streamlit frontend application
│   ├── add_update_ui.py     # UI for adding/updating expenses
│   ├── analytics_by_months.py # Monthly analytics module
│   ├── analytics_ui.py      # Expense category analytics
│   └── App.py               # Main entry point for Streamlit
├── TESTS/                   # Screenshots & test cases
│   ├── analytics_ui_demo1.png
│   ├── analytics_ui_demo2.png
│   └── app_frontend_ui.png
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies

🛠️ Setup & Installation
1. Clone the Repository
  git clone https://github.com/yourusername/expense-management-system.git
  cd expense-management-system

2. Install Dependencies
Make sure Python 3.8+ is installed, then run:
  pip install -r requirements.txt

3.Configure the Database
Set up your database (SQLite or MySQL) with a database named expense_manager. Update connection details in BACKEND/db_helper.py if necessary.

4. Start the FastAPI Backend
Launch the backend server with:
  uvicorn backend.server:app --reload

•API URL: http://127.0.0.1:8000
•API Docs: http://127.0.0.1:8000/docs

5. Run the Streamlit Frontend
Start the frontend application with:
streamlit run FRONTEND/App.py

•Frontend URL: http://localhost:8501


🧪 Running Tests
Execute the test suite to ensure both frontend and backend components work correctly:
pytest

🏗️ Tech Stack
    | **Component** | **Technology**          |
|--------------:|:------------------------|
| **Backend**   | FastAPI                |
| **Frontend**  | Streamlit              |
| **Database**  | SQLite / MySQL         |
| **Logging**   | Python Logging Module  |
| **Testing**   | Pytest                 |


 📢 Contributing
We welcome your contributions! To get started:
1. Fork the repository.
2. Create a feature branch:
git checkout -b feature-xyz
3.Commit your changes:
git commit -m "Add new feature"
4.Push to your fork:
git push origin feature-xyz
5.Create a Pull Request.
Every contribution is highly appreciated!


✉️ Contact
•Phone: +91 7340726877
•Email: burgalakrishnasavera@gmail.com
•GitHub: savera1226/

🚀 Track Smarter, Spend Better!
Empower your financial decisions with data-driven insights. Happy tracking and happy coding!

