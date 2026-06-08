
# Flask Calculator

A simple web-based calculator built with Flask that performs basic arithmetic operations:

- Addition (+)
- Subtraction (-)
- Multiplication (×)
- Division (÷)

## Features

- Clean and responsive UI
- Flask backend
- External CSS using Flask static files
- Error handling for division by zero

## Project Structure

```text
calculator/
│
├── app.py
├── static/
│   └── style.css
├── templates/
│   └── index.html
└── README.md
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/flask-calculator.git
cd flask-calculator
```

### 2. Create a virtual environment (Optional)

```bash
python -m venv venv
```

Activate it:

**Windows**
```bash
venv\Scripts\activate
```

**Linux/Mac**
```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install flask
```

## Run the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## Screenshot

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/2fb6ea74-171d-464e-a559-7f0b9d488a5e" />


### Calculator Home Page

![Calculator Screenshot](screenshots/calculator.png)

> Place your screenshot inside a folder named `screenshots` and name it `calculator.png`.

Project structure with screenshot:

```text
calculator/
│
├── screenshots/
│   └── calculator.png
│
├── static/
├── templates/
├── app.py
└── README.md
```

## Technologies Used

- Python
- Flask
- HTML5
- CSS3

## Author

Your Name

## License

This project is licensed under the MIT License.
