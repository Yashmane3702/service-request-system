
## 🚀 Features

### 👤 User Management
- User Registration  
- Secure Login (Password Hashing)  
- Session-based Authentication  
- Logout Functionality  

### 📝 Service Requests
- Create service requests with:
  - Title  
  - Description  
  - Category  
  - Priority (Low, Medium, High, Critical)  
- View all personal service requests  
- Track request status  
- Request timestamps (Created & Updated)

### 🗄 Database
- SQLite lightweight relational database  
- Two tables:
  - `users`
  - `service_requests`  
- Auto-table creation on startup

### 🎨 UI/UX
- Clean, mobile-friendly UI using **Bootstrap 5**  
- Flash messages for feedback  
- Consistent layout using Jinja templates

---

## 🏗️ System Architecture

Browser (Client)
↓
Flask Web Server (Python)
↓
Business Logic (app.py)
↓
SQLite Database
↓
HTML Templates (Jinja2 + Bootstrap)



## 🛠️ Tech Stack

| Layer | Technology |
|------|------------|
| Frontend | HTML, CSS  |
| Backend | Python  |
| Database | SQLite |
| Tools | Git, GitHub, Virtual Environment |

---

## 📁 Project Structure

service-request-system/
│
├── app.py
├── requirements.txt
├── .gitignore
└── templates/
├── base.html
├── index.html
├── login.html
├── register.html
├── dashboard.html
├── create_request.html
└── my_requests.html


---

## ▶️ How to Run the Project Locally

### 1️⃣ Clone the repository
git clone https://github.com/Yashmane3702/service-request-system.git
cd service-request-system

2️⃣ Create Virtual Environment
python -m venv .venv

3️⃣ Activate Virtual Environment
# Windows
.\.venv\Scripts\activate

# Mac/Linux
source .venv/bin/activate

4️⃣ Install Dependencies
pip install -r requirements.txt

5️⃣ Run the Application
python app.py

6️⃣ Open in Browser
http://127.0.0.1:5000/
