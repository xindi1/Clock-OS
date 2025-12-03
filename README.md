# Clock OS 1.0 – Five-Clock Temporal Engine

**Clock OS 1.0** is a lightweight, browser-based “time-based OS” that helps you understand your internal rhythms and choose the best next action.

Instead of just telling you what time it is, Clock OS tells you **what time it is *for you***.

---

## 🌐 Live Demo

Open the HTML file directly or host it (e.g., GitHub Pages):

- `clock-os-1.0.html`

On mobile (Safari, Chrome):
1. Open the page.
2. Use **Share → Add to Home Screen** to pin it like an app.

---

## 🧠 Core Concept

Clock OS combines five internal “clocks”:

1. **Sun Clock** – circadian alignment & daylight exposure  
2. **Focus Clock** – cognitive clarity and focus windows  
3. **Sleep Clock** – sleep timing, quality, and recovery state  
4. **Energy Clock** – physical and mental energy patterns  
5. **Priority Clock** – synthesizes all four into a **Readiness score** and recommends your **Best Next Action**

All data is stored locally in the browser using `localStorage` — no accounts, no sync, no server.

---

## 🖥 Features

- Real-time **local time** and **Readiness score**
- **Today Summary** bar:
  - Readiness • Focus • Energy • Sleep • Sun
- Quick logging for:
  - Sun exposure  
  - Focus sessions  
  - Last night’s sleep  
  - Energy check-ins  
- Per-clock tiles with:
  - Score (0–100)  
  - Current phase  
  - Key stats (logs, sessions, trend, consistency)
- **Priority Clock**:
  - Readiness 0–100
  - Mode (Deep Work, Focused Execution, Maintenance, Recovery, Balance)
  - Suggested window length for your next block

---

## 🛠 Tech Stack

- **HTML + CSS + Vanilla JavaScript**
- No frameworks, no backend
- Data stored in `localStorage`

To reset all data, click **“Reset data”** in the UI.

---

## 🚀 Getting Started

### Local

1. Download or clone the repo.
2. Open `clock-os-1.0.html` in your browser.
3. Start logging:
   - Sun exposure
   - Focus sessions
   - Sleep
   - Energy

### GitHub Pages

1. Push this repo to GitHub.
2. In **Settings → Pages**, set Source to:
   - Branch: `main` (or `master`)
   - Folder: `/root`
3. Save and use the generated URL.
4. On your phone, open the URL → **Add to Home Screen**.

---

## 🧭 How to Use It Day-to-Day

- Log **once or twice per block** rather than obsessing:
  - 1–2 sun logs
  - 1–3 focus blocks
  - 1 sleep log per day
  - 2–4 energy check-ins
- Use the **Readiness score + Priority suggestion** to decide:
  - Deep work vs admin
  - Rest vs push
  - When to plan vs when to execute

The more you log, the smarter the clocks get.

---

## 📌 Roadmap (Future Ideas)

- Dedicated **Trading Clock**, **Workout Clock**, **Learning Clock**
- Weekly insight view (streaks, patterns, personal “prime time”)
- Optional export of logs (CSV/JSON)

---

## License

TBD – personal prototype / experimental project for now.
