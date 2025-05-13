# 💳 Bankist App

Bankist is a front-end banking interface simulation that showcases modern JavaScript capabilities in building responsive, dynamic, and interactive web applications without a backend. It mimics core banking functionalities such as login, fund transfers, loan approval logic, and account management using only client-side logic.

---

## 🎯 Purpose

This project was developed as a part of mastering DOM manipulation, event-driven programming, and JavaScript’s capabilities in formatting, timers, and UX behavior. It serves as a learning and demonstration tool to replicate real-world banking flows and responsive interface behavior with clean, minimal design.

---

## 🧑‍💻 Use Cases

- Demonstrate interactive web app capabilities using **Vanilla JS**
- Learn how to dynamically update the DOM based on user input
- Practice working with:
  - Array methods (`map`, `filter`, `reduce`, `forEach`)
  - Date and time formatting with `Intl` API
  - Currency formatting for multiple locales
  - Event-driven form handling
  - Auto logout timers (simulated session management)

---

## 🚀 Features

- User authentication with username and PIN
- Transaction (deposit/withdrawal) history with timestamps
- Balance and summary (in/out/interest) computation
- Fund transfers between accounts
- Simulated loan approval logic
- Auto logout after inactivity (timer reset on actions)
- Account closure functionality
- Currency formatting based on user locale
- Responsive and minimalist UI
- Fully client-side – no backend or database needed

---

## 🛠️ Tech Stack

| Layer            | Technology                     |
|------------------|--------------------------------|
| Markup           | HTML5                          |
| Styling          | CSS3 (Responsive, Flexbox)     |
| Logic/Functionality | JavaScript (ES6+)          |
| Fonts            | Google Fonts - Poppins         |
| Tools/Settings   | Prettier for code formatting   |
| Media Assets     | PNG files (logo, icons)        |

---

## 💡 Skills Demonstrated

- DOM Manipulation (`querySelector`, `addEventListener`)
- JavaScript Object and Array operations
- Event delegation and form handling
- Date/time parsing and formatting with `Date` and `Intl.DateTimeFormat`
- Currency formatting with `Intl.NumberFormat`
- Use of higher-order array functions: `map`, `filter`, `reduce`, `some`, `every`, `find`, `sort`
- Basic animation via dynamic class toggling
- Responsive CSS and form design
- Timer management with `setTimeout` and `clearTimeout`

---

## 🗂️ Folder Structure

Bankist-App/
│
├── index.html # Main HTML page with structure and login form
├── style.css # Responsive styling with custom fonts and layout
├── script.js # Core JavaScript logic (accounts, transfers, loans, DOM updates)
├── logo.png # Bankist app logo
├── icon.png # Favicon for the tab
├── Bankist-flowchart.png # Flow diagram showing UX interactions
├── .prettierrc # Prettier config for formatting
├── .Rhistory # (Not relevant — can be ignored or removed)

yaml
Copy
Edit

---

## 🧪 How to Run

1. Download or clone the repository.
2. Open the `index.html` file in any modern web browser.
3. Use one of the predefined login credentials:

Username: js | PIN: 1111 (Jonas Schmedtmann)
Username: jd | PIN: 2222 (Jessica Davis)

yaml
Copy
Edit

---

## 📊 Account Sample Data

```javascript
const account1 = {
  owner: 'Jonas Schmedtmann',
  movements: [200, 455.23, -306.5, 25000, -642.21, -133.9, 79.97, 1300],
  interestRate: 1.2,
  pin: 1111,
  movementsDates: [...],
  currency: 'EUR',
  locale: 'pt-PT',
};

const account2 = {
  owner: 'Jessica Davis',
  movements: [5000, 3400, -150, -790, -3210, -1000, 8500, -30],
  interestRate: 1.5,
  pin: 2222,
  movementsDates: [...],
  currency: 'USD',
  locale: 'en-US',
};
📈 Enhancement Ideas
Integrate backend to store and retrieve real data

Add transaction categorization or filtering

Implement authentication with token-based sessions

Add dark/light theme toggling

Expand multi-user support with profile settings
