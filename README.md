# calculator-app
Scientific Calculator

Overview

This is a simple web-based scientific calculator built with HTML, CSS, and JavaScript.
It supports basic arithmetic operations and scientific functions like sin, cos, tan, log, and ln.

---

Features

- Basic operations: "+ − × ÷"
- Powers: "x²", "xʸ"
- Square root: "√"
- Constants: "π"
- Trigonometric functions: "sin", "cos", "tan" (in degrees)
- Logarithms:
  - "log" → base 10
  - "ln" → natural log
- Input helpers:
  - Auto converts "sin 30" → "sin(30)"
  - Delete (DEL) and Clear (C)

---

Important Notes

1. Trigonometric Functions

- All trig functions use degrees, not radians.
- Example:
  - "sin(30)" → "0.5"
  - "cos(60)" → "0.5"
  - "tan(45)" → "1"

---

2. Input Format

You can enter expressions in two ways:

✅ Recommended:

sin(30)
cos(45)
tan(40)

✅ Also supported:

sin 30
cos 45
tan 40

The calculator automatically converts them internally.

---

3. Log Functions

log(100) → 2
ln(2.718) → ~1

---

4. Power Function

Use:

Math.pow(2,3) → 8

Or via buttons:

- Press "xʸ"
- Enter values separated by ","

---

How It Works

- User input is displayed in the screen.
- Before evaluation:
  - Expressions like "sin 30" are converted to "sin(30)"
- JavaScript "eval()" is used to compute the result.
- Custom functions convert degrees → radians for trig calculations.

---

Known Limitations

- Uses "eval()" (not fully secure for advanced use cases)
- Requires proper syntax for complex expressions
- No bracket auto-completion

---

Future Improvements (Optional)

- DEG/RAD toggle switch
- Safer expression parser (replace "eval")
- Keyboard input support
- Calculation history
- Improved UI (Casio-style layout)

---

Author Note

This project is ideal for learning:

- DOM manipulation
- Event handling
- Basic math processing in JavaScript
