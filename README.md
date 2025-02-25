💰 Expense Tracking System 🚀
📊 Your Smart, Fast, and Efficient Expense Manager

The Expense Tracking System is a modern, full-stack application designed to help individuals and businesses track expenses effortlessly. Powered by FastAPI (backend) and Streamlit (frontend), it offers a smooth, high-performance experience with real-time analytics and insights.

🔥 Features
✅ Seamless Expense Tracking – Add, edit, and delete expenses with ease.
✅ Monthly & Category-Based Analytics – Gain insights into spending habits.
✅ Intuitive & Interactive UI – Built with Streamlit for a dynamic experience.
✅ Lightning-Fast API – FastAPI ensures high-speed, scalable performance.
✅ Modular & Scalable – Designed with best practices for future enhancements.

📁 Project Structure
bash
Copy
Edit
expense_tracking_system/
│
├── BACKEND/                    # FastAPI backend server
│   ├── __init__.py             # Package initializer
│   ├── db_helper.py            # Handles database interactions
│   ├── logging_setup.py        # Logging configuration
│   ├── my_app.log              # Log file for tracking errors/events
│   ├── server.log              # API request logs
│   ├── server.py               # Main FastAPI server
│
├── FRONTEND/                   # Streamlit frontend application
│   ├── add_update_ui.py        # UI for adding/updating expenses
│   ├── analytics_by_months.py  # Monthly analytics module
│   ├── analytics_ui.py         # Expense category analytics
│   ├── App.py                  # Main entry point for Streamlit
│
├── TESTS/                      # Screenshots and test cases
│   ├── analytics_ui_demo1.png  # UI Screenshot
│   ├── analytics_ui_demo2.png  # UI Screenshot
│   ├── app_frontend_ui.png     # UI Screenshot
│
├── README.md                   # Project documentation
├── requirements.txt            # Python dependencies
🛠️ Setup & Installation
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/expense-management-system.git
cd expense-management-system
2️⃣ Install Dependencies
Ensure Python 3.8+ is installed, then run:

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Start the FastAPI Backend
bash
Copy
Edit
uvicorn backend.server:app --reload
🔗 The API is available at: http://127.0.0.1:8000
📜 Automatic API docs at: http://127.0.0.1:8000/docs

4️⃣ Run the Streamlit Frontend
bash
Copy
Edit
streamlit run frontend/App.py
🎨 Open http://localhost:8501 in your browser!

🧪 Running Tests
Execute all tests using:

bash
Copy
Edit
pytest
This ensures both frontend and backend components are functioning correctly.

🏗️ Tech Stack
Component	Technology
Backend	FastAPI
Frontend	Streamlit
Database	SQLite / MySQL
Logging	Python Logging Module
Testing	Pytest
📢 Contributing
We welcome contributions! 🚀

Fork the repository.
Create a feature branch (git checkout -b feature-xyz).
Commit your changes (git commit -m "Added new feature").
Push to your fork (git push origin feature-xyz).
Create a Pull Request!


✉️ Contact +91 7340726877
📩 Have questions? Reach out at: burgalakrishnasavera@gmail.com
🔗 Check out more projects on GitHub

🚀 Track Smarter, Spend Better! 💰
