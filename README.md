# Investment Calculator (Django)

An investment calculator built with **Django**, designed to help users project future investment returns based on initial capital, interest rate, and duration.

## Features

- Handles both **GET** and **POST** requests using class-based views
- Calculates investment growth using principal, rate, and time
- Clean, responsive UI using **Bootstrap** and **Crispy Forms**
---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/d675b5d4-72f3-4ab7-b9de-4e548a2abc1c)

![image](https://github.com/user-attachments/assets/64d057f1-4be7-4ff4-b4f1-71e42073b0b9)


## Tech Stack

| Technology      | Description                      |
|------------------|----------------------------------|
| **Python**        | Backend logic                   |
| **Django**        | Web framework (MVC)             |
| **HTML/CSS**      | Page layout and styling         |
| **Bootstrap**     | UI styling                      |
| **Crispy Forms**  | Enhanced Django form rendering  |

## How to run this on your machine:

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/investment-calculator.git
cd investment-calculator

```
### 2. Create virtual environment (Windows)

```bash
python -m venv venv
env\Scripts\activate   # Windows
# OR
source venv/bin/activate   # macOS/Linux
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run server 
```bash
python manage.py runserver
```

Then open your browser and visit http://localhost:8000

###

This is scalable and easy to build on. Some things i plan to add in the future are:
- Adding compound interest options (monthly/yearly)
- Chart visualization with Chart.js
- Add user login to save history
