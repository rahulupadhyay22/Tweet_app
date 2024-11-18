# Tweet App

This is a simple Tweet App built with **Python-Django** and **Bootstrap**. The app allows users to register, log in, and perform CRUD (Create, Read, Update, Delete) operations on their tweets. Each user can only manage their own tweets, ensuring a secure and personalized experience.

---

## Features

- **User Authentication**:
  - User Registration
  - User Login/Logout
- **Tweet Management**:
  - Create tweets
  - View all tweets
  - Update tweets (only by the creator)
  - Delete tweets (only by the creator)
- **Responsive Design**:
  - Styled using **Bootstrap** for a clean and responsive interface.

---

## Installation

Follow these steps to set up and run the project locally.

### Prerequisites
- Python 3.x
- pip (Python package manager)
- A virtual environment (optional but recommended)

### Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/tweet-app.git
    cd tweet-app
    ```

2. **Set up a virtual environment**:
    ```bash
    python -m venv env
    source env/bin/activate   # On Windows: env\Scripts\activate
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations**:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. **Run the development server**:
    ```bash
    python manage.py runserver
    ```

6. Open your browser and navigate to:  
    `http://127.0.0.1:8000/`

---

## Usage

1. **Register**: Create an account by signing up.
2. **Login**: Log in using your credentials.
3. **Create Tweets**: Add your thoughts by creating new tweets.
4. **Manage Tweets**: Update or delete your tweets as needed.
5. **Logout**: Securely log out from the application.

---

## Technologies Used

- **Backend**: Python-Django
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (default Django database)
- **Authentication**: Django's built-in user authentication system

---

## Contributing

Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Make your changes and commit:
    ```bash
    git commit -m "Add some feature"
    ```
4. Push to your branch:
    ```bash
    git push origin feature-name
    ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For any queries or suggestions, please feel free to reach out:

- **Email**: rahulu825@gmail.com
- **GitHub**: https://github.com/rahulupadhyay22

---

Thank you for checking out the Tweet App! 🎉

