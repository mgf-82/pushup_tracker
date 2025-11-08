Push-up Tracker

A lightweight browser-based app for tracking daily push-ups.
No server, no signup — all data stays in your browser via localStorage.

🔧 Features

Add and manage sets with date, reps, and notes

Automatic summaries: daily, weekly, and all-time totals

Progress chart (Chart.js) for visual trends

Adjustable daily target with live percentage feedback

Expandable log view grouped by month and day

Export / Import JSON for backup or transfer

All data stored locally — no internet or backend required

🚀 How to Run

Clone or download this repository

Open pushup-tracker.html in any modern web browser

Start adding push-up entries — data saves automatically

📁 File Structure
pushup-tracker.html


Contains all HTML, CSS, and JavaScript inline

Uses Chart.js 4.4.0
 via CDN

No dependencies or build steps

💾 Data Storage

Data is stored in localStorage under key pushup.tracker.v1:

{
  "entries": [
    { "id": "...", "date": "2025-11-08", "reps": 30, "note": "Standard", "createdAt": 1762310267942 }
  ],
  "target": 30
}


Use Export JSON to download your log or Import JSON to restore it.

🧩 Keyboard Shortcuts / Tips

Use Tab / Enter to quickly move between inputs

Change “Show last” dropdown to view 7, 14, 30, or 90-day charts

Reset all clears data permanently (use with caution)

📜 License

MIT License — free for personal or commercial use.
