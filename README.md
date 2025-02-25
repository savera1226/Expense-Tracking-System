# 💰 Expense Tracking System 🚀
**📊 Your Smart, Fast, and Efficient Expense Manager**

The **Expense Tracking System** is a modern, full-stack application designed to help individuals and businesses track expenses effortlessly. Powered by **FastAPI** (backend) and **Streamlit** (frontend), it offers a smooth, high-performance experience with real-time analytics and insights.

---

## 🛠 Setup & Installation

### **1️⃣ Clone the Repository**
bash
git clone https://github.com/yourusername/expense-management-system.git
cd expense-management-system


### **2️⃣ Install Dependencies**
Make sure **Python 3.8+** is installed, then run:
bash
pip install -r requirements.txt


### **3️⃣ Configure the Database**
Set up your database (**SQLite or MySQL**) with a database named **expense_manager**.  
Update connection details in **`BACKEND/db_helper.py`** if necessary.

### **4️⃣ Start the FastAPI Backend**
Launch the backend server:
bash
uvicorn backend.server:app --reload

- **API URL:** [http://127.0.0.1:8000](http://127.0.0.1:8000)  
- **API Docs:** [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)  

### **5️⃣ Run the Streamlit Frontend**
Start the frontend application:
bash
streamlit run FRONTEND/App.py

- **Frontend URL:** [http://localhost:8501](http://localhost:8501)  

---

## 🧪 Running Tests
To verify both frontend and backend components work correctly:
bash
pytest


---

## 🚀 Tech Stack

| **Component**  | **Technology**     |
|--------------|-----------------|
| **Backend**  | FastAPI         |
| **Frontend** | Streamlit       |
| **Database** | SQLite / MySQL  |
| **Logging**  | Python Logging  |
| **Testing**  | Pytest          |

---

## 📢 Contributing

We welcome your contributions! To get started:

1. **Fork the repository.**
2. **Create a feature branch:**
   bash
   git checkout -b feature-xyz
   
3. **Commit your changes:**
   bash
   git commit -m "Add new feature"
   
4. **Push to your fork:**
   bash
   git push origin feature-xyz
   ```
5. *Create a Pull Request.*

Every contribution is highly appreciated!

---

## ✉ Contact

- 📞 *Phone:* +91 7340726877  
- 📧 *Email:* burgalakrishnasavera@gmail.com  
- 💻 *GitHub:* [savera1226](https://github.com/savera1226)  

---
