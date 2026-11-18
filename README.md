# 🧮 Simple Calculator Web

An interactive web calculator application developed using **HTML5**, **CSS3**, and **vanilla JavaScript**, focused on the study of DOM manipulation and local data persistence.

---

## 🚀 Features

* **Basic Operations:** Addition (`+`), Subtraction (`-`), Multiplication (`*`), and Division (`/`).
* **Dynamic Calculation:** Mathematical expressions are evaluated upon clicking the `=` button, with the result displayed immediately on the screen.
* **Screen Clearing (`Clear`):** A button to reset the calculation and clear the stored history.
* **Data Persistence (`localStorage`):** The current calculation is automatically saved in the browser, allowing the previous state to be maintained even after refreshing the page.

---

## 🛠️ Technologies Used

* **HTML5:** Structure for the buttons and the result display, as well as the inclusion of scripts.
* **CSS3:** Visual styling inspired by standard calculators (rounded buttons in shades of gray and orange, dark theme).
* **JavaScript:** Logic for updating expressions, DOM manipulation, and `localStorage` management.

---

## 📂 File Structure

```text
Calculadora/
│
├── index.html       # Main calculator structure and button events
│
├── styles/
│   └── calculator.css    # Visual styling of the buttons and display
│
└── scripts/
    └── calculator.js     # Calculation logic and persistence in localStorage
```

## ⚠️ Learning Note

* **Note:** This project uses JavaScript’s native `eval()` function to calculate the result of expressions. This approach was employed strictly for educational and learning purposes. In actual production projects, it is recommended to avoid using `eval()` due to potential security risks.
