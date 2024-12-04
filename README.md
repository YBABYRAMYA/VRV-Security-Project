# ✨ Flask Authentication System with RBAC ✨

Welcome to the Flask Authentication System with Role-Based Access Control (RBAC)! This project offers a secure, scalable, and user-friendly framework for managing authentication, user registration, and role-based access in a web application.

🚀 Features 🚀
🛡 User Authentication: Secure login and logout to protect user sessions.
✍ User Registration: Seamless sign-up process for new users.
📄 Role-Based Access Control (RBAC): Role-specific content and functionality (e.g., Admin, Editor, Viewer).
🎨 Responsive UI: Elegant and modern design with Bootstrap for optimal usability.
🔒 Secure Sessions: User sessions are safely managed using Flask's session framework.
⚙️ Extendable Architecture: Easily add custom roles and permissions as your application grows.

🔋 Tech Stack
Backend: Flask, Flask-Bcrypt, Flask-SQLAlchemy, Flask-WTF
Frontend: HTML5, CSS3, Bootstrap
Database: SQLite (can be swapped with MySQL or PostgreSQL for production)


## 🗃️ Project Structure

├── app.py                  # Main application file
├── static/
│   └── styles.css          # Custom CSS for styling
├── templates/
│   ├── index.html          # Home page template
│   ├── register.html       # User registration template
│   ├── login.html          # User login template
│   └── dashboard.html      # Dashboard template
├── requirements.txt        # Required Python packages
└── README.md               # Project documentation


## Setup Instructions 🛠️

Follow these steps to get started with the project:

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd VRV
   ```

3. **Activate Virtual Environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Application**:
   ```bash
   python app.py
   ```

6. Access the Application
🌐 Home: http://127.0.0.1:5000/
🔒 Login: http://127.0.0.1:5000/login
📝 Register: http://127.0.0.1:5000/register

📜 Routes Overview
/ - Home Page
/login - User Login
/register - User Registration
/dashboard - User Dashboard
/logout - User Logout


## Screenshots 📸

### Homepage 🏠
![Homepage](https://github.com/user-attachments/assets/85fe5c08-48cd-4e92-bff8-38650a5d3abf)

### Dashboard 📊
![dashboard](https://github.com/user-attachments/assets/340a5d3d-ea3e-4604-a10c-33103cb65f1a)

### Login Page 🔑
![login](https://github.com/user-attachments/assets/8a4b8ada-d993-4dde-84ab-fad4678a0fbc)


### Registration Page 📝
![register](https://github.com/user-attachments/assets/72ea7139-fdf6-4575-9dea-7f8fe476ed9f)


💎 Key Features of the Dashboard
Dynamic Views: Displays content tailored to user roles.
Admin Privileges: Admin users can manage other users, view analytics, or access privileged data.
Activity Overview: Showcases recent user actions, notifications, or system stats.
Responsive Design: Ensures functionality across devices.


## File Descriptions 📄

- **`app.py`**: The main script that initializes and runs the Flask application.
- **`instance/users.db`**: SQLite database file for user data.
- **`templates/`**: Contains the following HTML templates:
  - `dashboard.html`: User dashboard.
  - `index.html`: Homepage.
  - `login.html`: Login page.
  - `register.html`: Registration page.
- **`venv/`**: Virtual environment directory for managing dependencies.


## Contributing 🤝

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License 📜

This project is licensed under the MIT License.

---

Feel free to explore and enhance the project! 🌟

