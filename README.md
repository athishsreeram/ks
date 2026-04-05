# 💸 ks – Attendance & Cost Tracker

**Don’t let missed classes drain your wallet unnoticed.**  
A dead‑simple, no‑login web app that shows you exactly how much money is lost when your kid misses a class.

👉 **Live demo:** [athishsreeram.github.io/ks](https://athishsreeram.github.io/ks/)

![KS Screenshot](https://via.placeholder.com/800x400?text=Attendance+Tracker+in+Action)  
*(Replace with an actual screenshot of the app)*

---

## ✨ Why this exists

- Your kid misses a class → you lose money.
- But without tracking, the loss stays invisible.
- **ks** turns every absence into a visible cost – so you stay aware and in control.

---

## 🚀 Features

- **Mark attendance in seconds** – click present/absent for each class session.
- **💸 “Wasted this month”** – real‑time calculation of lost money.
- **No login, no backend** – runs entirely in your browser.
- **Local data persistence** – your attendance records stay on your device (using `localStorage`).
- **Clean, distraction‑free UI** – works on desktop, tablet, and mobile.
- **Customizable cost per class** – set your own monthly fee or per‑session rate.
- **Month / week view** – easily see past and upcoming classes.

---

## 📊 How it works

1. **Set up** – enter the cost per class (or monthly total).
2. **Mark attendance** – tap “Present” or “Absent” for each scheduled class.
3. **See the waste** – the dashboard shows:
   - Total classes this month
   - Classes attended
   - Classes missed
   - **Money wasted** (missed × cost per class)
4. **Data stays private** – no server, no sign‑up, no tracking.

---

## 🧪 Local development

Run the project on your own machine:

```bash
git clone https://github.com/athishsreeram/ks.git
cd ks
```

Open `index.html` in any modern browser – no build steps, no dependencies.

### Project structure (typical)
```
ks/
├── index.html      # main UI and layout
├── style.css       # styling, responsive design
├── script.js       # attendance logic, cost calculation, localStorage
└── README.md       # this file
```

---

## 🛠️ Built with

- **HTML5** – semantic structure
- **CSS3** – Flexbox/Grid, clean and mobile‑first design
- **Vanilla JavaScript** – event handling, data persistence (`localStorage`), dynamic UI updates

---

## 📌 Use cases

- **Parents** of kids attending tuition, sports, music, or any paid class.
- **Small tutoring centers** (offline‑first, no login for each parent).
- **Anyone** who pays for recurring sessions and wants to track actual attendance.

---

## 🤝 Contributing

Ideas or improvements? Pull requests are welcome!

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/improvement`).
3. Commit your changes (`git commit -m 'Add weekly summary'`).
4. Push to the branch (`git push origin feature/improvement`).
5. Open a Pull Request.

Please keep the app **dead‑simple** – no login, no backend, no complexity.

---

## 📄 License

This project is open source under the **MIT License**.  
Feel free to use, modify, and share it – see the [LICENSE](LICENSE) file for details (if none exists, you may add one).

---

## 🙏 Acknowledgements

Inspired by the simple truth:  
*“What gets measured, gets managed.”* – and wasted money should never be invisible.

---

*Stop losing money to missed classes. Start tracking today.* 💸
