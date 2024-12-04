# ✨ Flask Authentication System with RBAC ✨

Welcome to the **Flask Authentication System** with Role-Based Access Control (RBAC)! This project provides a robust framework for user authentication, registration, and role-based dashboard management using Flask.

---

## 🚀 Features 🚀

- 🛡 **User Authentication**: Secure login and logout functionality to safeguard user data.
- ✍ **User Registration**: Allows new users to sign up with ease.
- 🎨 **Responsive UI**: Modern and clean Bootstrap-styled pages for an enhanced user experience.
- 📄 **Role-Based Access Control (RBAC)**: Dynamic redirection and content display based on user roles.
- 🔒 **Secure Sessions**: Robust session management powered by Flask.
- ⚙️ **Extendable Architecture**: Easily add new roles and permissions.

---

## 🔋 Tech Stack 🔋

- **Backend**: Flask, Flask-Bcrypt, Flask-SQLAlchemy, Flask-WTF
- **Frontend**: HTML5, CSS3, Bootstrap
- **Database**: SQLite (can be swapped for other SQL-based databases)

---

## 🗃️ Project Structure 🗃️

├── app.py
├── static
│   └── styles.css
├── templates
│   ├── index.html
│   ├── register.html
│   ├── login.html
│   └── dashboard.html
└── requirements.txt


---

## 🛠️ Setup Instructions 🛠️

### 1⃣ Install Dependencies
Ensure you have Python installed. Then, install the required Python packages:

bash
pip install flask flask-bcrypt flask-sqlalchemy flask-wtf


### 2⃣ Run the Application
Start the Flask development server by running the following command:

bash
python app.py


### 3⃣ Access the Application
Open your browser and navigate to the following endpoints:

- 🌐 **Home**: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)
- 🔒 **Login**: [http://127.0.0.1:5000/login](http://127.0.0.1:5000/login)
- 📝 **Register**: [http://127.0.0.1:5000/register](http://127.0.0.1:5000/register)

---

## 📜 Routes 📜

- / - Home Page
- /login - User Login
- /register - User Registration
- /dashboard - User Dashboard
- /logout - User Logout

---

## 🎨 Screenshots 🎨

### 🏠 Home Page
![Screenshot (1317)](https://github.com/user-attachments/assets/ce83d200-6fd2-41b8-95f6-258410dd1310)

### 🔒 Login Page
![Screenshot (1314)](https://github.com/user-attachments/assets/b1cbba15-9feb-4b2a-9c24-f0df2e4b23be)

### 📝 Registration Page
![Screenshot (1315)](https://github.com/user-attachments/assets/2bce110e-dfd9-4c06-b623-4ab654208bfc)

### 🔹 Dashboard
![Screenshot (1316)](https://github.com/user-attachments/assets/844deefa-2967-4470-9f9f-ae2a1fc7b063)

---

## 💎 Key Features of the Dashboard

- **Personalized Experience**: Displays user-specific content.
- **Role-Based Controls**: Tailored views based on user roles (e.g., admin, editor, viewer).
- **Activity Overview**: Shows recent actions and statistics.
- **Responsive Design**: Ensures usability across devices.

---

## 🤝 Contributing

We welcome contributions to make this project even better! Here’s how you can contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Submit a pull request for review.

---

## 📝 License

This project is licensed under the **MIT License**. For more details, see the LICENSE file in the repository.

---

## ❤ Acknowledgments

- **Flask**: For providing a lightweight and flexible web framework.
- **Bootstrap**: For the beautiful and responsive UI components.
- **Open Source Community**: For inspiration and valuable tools.

---
