# 🧮 Calculator

A simple and interactive *Calculator* built using *Python, Flask, HTML, CSS, and JavaScript*.

The calculator supports basic arithmetic operations along with several scientific functions such as trigonometry, logarithms, square roots, powers, factorials, and so on.

## 🚀 Features

- ➕ Addition
- ➖ Subtraction
- ✖️ Multiplication
- ➗ Division
- 🔢 Decimal and percentage calculations
- 📐 Trigonometric functions
  - sin
  - cos
  - tan
  - sin⁻¹
  - cos⁻¹
  - tan⁻¹
- √ Square root
- xʸ Power calculation
- x² Square
- x! Factorial
- log and ln
- π and e constants
- DEG / RAD angle modes
- 🧹 Clear and delete functions
- ⌨️ Keyboard support
- 📜 Calculation history
- 📱 Responsive design
- ⚡ Flask backend for calculations

## 🛠️ Technologies Used

- *Python*
- *Flask*
- *HTML5*
- *CSS3*
- *JavaScript*

## 📂 Project Structure

text
Calculator/
│
├── static/
│   ├── script.js
│   └── style.css
│
├── templates/
│   └── index.html
│
├── main.py
├── requirements.txt
└── README.md


## ⚙️ Installation

### 1. Clone the repository

bash
git clone https://github.com/riktaghosh114/My-Calculator.git


### 2. Open the project folder

bash
cd My-Calculator


### 3. Install the required packages

bash
pip install -r requirements.txt


### 4. Run the Flask application

bash
python main.py


### 5. Open in your browser

Go to:

text
http://127.0.0.1:5000


## 🧮 Example Calculations

text
25 + 15
10 × 5
100 ÷ 4
sqrt(144)
5^2
sin(30)
log(100)
5!


## 🔐 Security

The calculator uses Python's ast module to parse mathematical expressions instead of directly using Python's eval() function.

Only supported mathematical operations, constants, and functions are allowed.

## 📌 Future Improvements

- Memory functions (M+, M-, MR, MC)
- More scientific functions
- Persistent calculation history
- Dark/light theme switch
- Improved mobile UI
- More advanced mathematical operations

## 👨‍💻 Author

GitHub: *riktaghosh114*

---

⭐ If you like this project, consider giving the repository a star!
