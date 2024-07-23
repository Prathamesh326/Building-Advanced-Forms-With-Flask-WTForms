# Flask Login Example

This project is a simple Flask application that demonstrates how to implement a login form using Flask, Flask-WTF for form handling, and Flask-Bootstrap for styling.

## Features

- **Flask-WTF** for form handling and validation.
- **Flask-Bootstrap** for integrating Bootstrap 5 styles.
- Simple login logic with hardcoded credentials.
- Custom templates for home, login, success, and access denied pages.

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/Prathamesh326/Building-Advanced-Forms-With-Flask-WTForms.git
   cd Building-Advanced-Forms-With-Flask-WTForms
   ```

2. **Create and activate a virtual environment:**

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the dependencies:**

   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. **Run the application:**

   ```sh
   python main.py
   ```

2. **Open your web browser and visit:**

   ```
   http://127.0.0.1:5000/
   ```

3. **Login with the following credentials:**

   - **Email:** `admin@email.com`
   - **Password:** `12345678`

## Project Structure

```plaintext
.
├── main.py
├── templates
│   ├── base.html
│   ├── index.html
│   ├── login.html
│   ├── success.html
│   └── denied.html
└── requirements.txt
```

- `main.py`: The main Flask application file.
- `templates/`: Directory containing HTML templates.
  - `base.html`: Base template with common layout and styles.
  - `index.html`: Home page template.
  - `login.html`: Login page template.
  - `success.html`: Success page template displayed after successful login.
  - `denied.html`: Access denied page template displayed after failed login attempt.
- `requirements.txt`: List of Python dependencies.

## Dependencies

- Flask
- Flask-WTF
- Flask-Bootstrap
