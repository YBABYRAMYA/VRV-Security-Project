# VRV Project 🚀

Welcome to the **VRV Security Project**! This project is designed to provide a dynamic and robust framework for web development, utilizing Python and Flask. Here's a quick overview of the project structure and details.

## Project Structure 🗂️

```
VRV/
├── app.py          # Main application file 🐍
├── instance/       # Instance folder for database and configurations 🛠️
│   └── users.db    # SQLite database 📂
├── templates/      # HTML templates for the web pages 🎨
│   ├── dashboard.html
│   ├── index.html
│   ├── login.html
│   └── register.html
└── venv/           # Virtual environment for dependencies 🌐
    ├── Include
    ├── Lib
    ├── pyvenv.cfg
    └── Scripts
```

## Features ✨

- **Flask Framework**: A lightweight and flexible Python web framework.
- **SQLite Database**: For storing user data efficiently.
- **Dynamic Templates**: HTML templates for a responsive and engaging user interface.
- **Virtual Environment**: Ensures project dependencies are isolated and manageable.

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

6. **Access the Application**:
   Open your browser and navigate to `http://127.0.0.1:5000/` 🌐

## Screenshots 📸

### Homepage 🏠
![Homepage](screenshots/homepage.png)

### Dashboard 📊
![Dashboard](screenshots/dashboard.png)

### Login Page 🔑
![Login Page](screenshots/login.png)

### Registration Page 📝
![Registration Page](screenshots/register.png)

## File Descriptions 📄

- **`app.py`**: The main script that initializes and runs the Flask application.
- **`instance/users.db`**: SQLite database file for user data.
- **`templates/`**: Contains the following HTML templates:
  - `dashboard.html`: User dashboard.
  - `index.html`: Homepage.
  - `login.html`: Login page.
  - `register.html`: Registration page.
- **`venv/`**: Virtual environment directory for managing dependencies.

## Technologies Used 🛠️

- **Python** 🐍
- **Flask** 🌐
- **SQLite** 📂
- **HTML/CSS** 🎨

## Contributing 🤝

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License 📜

This project is licensed under the MIT License.

---

Feel free to explore and enhance the project! 🌟

