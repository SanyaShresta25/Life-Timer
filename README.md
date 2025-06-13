# ⏳ Life Timer

A simple JavaScript-based web app that lets users enter their date of birth (DOB) and then shows their age updating live in years, months, days, hours, minutes, and seconds.

---

## 🔧 Features

* 🔁 Real-time age update from entered DOB
* 📅 Toggle to open/close DOB input
* 💾 Saves DOB in browser local storage
* 🎨 Responsive UI with Font Awesome settings icon

---

## 🛠️ Tech Stack

* **HTML5** – Structure of the app
* **CSS3** – Custom styling (see `style.css`)
* **Vanilla JavaScript** – All logic handled with plain JS

---

## 📁 File Structure

```
life-timer/
├── index.html         # HTML markup
├── style.css          # Styling rules
└── index.js           # Main JavaScript logic
```

---

## 🚀 Getting Started

1. **Clone or Download** the repository.
2. Open `index.html` in a browser.
3. Click the ⚙️ settings icon and enter your DOB.
4. Watch your life timer update in real-time!

---

## 🔐 Local Storage

The app uses `localStorage` to remember your DOB so you don’t need to re-enter it on refresh:

```js
localStorage.setItem("year", dateOfBirth.getFullYear());
localStorage.setItem("month", dateOfBirth.getMonth());
localStorage.setItem("date", dateOfBirth.getDate());
```

---

## 📄 License

MIT License. Free to use and modify.

---

## 👩‍💻 Author

**Sanya Shresta Jathanna**
[GitHub – @SanyaShresta25](https://github.com/SanyaShresta25)

[Portfolio](https://sanyashresta.netlify.app/)
