# 💪 Weekly Grind — Workout Tracker

> A lightweight, offline-ready workout checklist built for the 5am crew. No app store. No subscription. Just you and the iron.

![HTML](https://img.shields.io/badge/HTML-Single%20File-4da6ff?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-Vanilla-5a6a82?style=flat-square&logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/JS-No%20Framework-4da6ff?style=flat-square&logo=javascript&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-Safari%20Ready-5a6a82?style=flat-square&logo=apple&logoColor=white)

-----

## 📋 The Program

A 5-day push/pull/legs split, Mon–Fri, with spirit and cardio baked in every day.

|Day        |Focus               |Highlight                            |
|-----------|--------------------|-------------------------------------|
|🏋️ Monday   |Shoulders & Core    |Arnold Press, Leg Raises, Shrugs     |
|💪 Tuesday  |Back & Biceps       |Lat Pulldown, Rows, Cable Curls      |
|🦵 Wednesday|Legs                |Squats, Calf Raises, Hamstrings      |
|🔥 Thursday |Arms, Core & Running|Barbell Curls, Triceps, 1-Mile Run   |
|🏆 Friday   |Chest & Triceps     |Bench Press, Fly, Incline, Cable Pull|


> 📖 Bible reading + 15-min treadmill walk included Mon, Tue, Wed & Fri.

-----

## ✨ Features

- **Daily checklists** — check off individual exercises or mark the whole day complete
- **Weekly progress bar** — visual 0–5 day completion tracker
- **Auto-reset** — detects Monday at 5:00 AM CDT and wipes the slate clean
- **Manual reset** — reset button in the bottom bar for fresh starts
- **Today detection** — automatically expands and highlights the current day
- **Persistent state** — progress is saved in `localStorage` between visits
- **iOS Reminders integration** — 5:00 AM recurring reminders, Mon–Fri, with full exercise lists in the notes
- **Offline ready** — single HTML file, no dependencies, no build step

-----

## 🚀 Getting Started

### Option 1 — Open directly in your browser

Just download `workout-tracker.html` and open it. That’s it.

```bash
git clone https://github.com/yourusername/weekly-grind.git
cd weekly-grind
open workout-tracker.html
```

### Option 2 — Add to iPhone Home Screen (Recommended)

1. Open `workout-tracker.html` in **Safari on iOS**
1. Tap the **Share** button `⎙`
1. Tap **“Add to Home Screen”**
1. Name it `Weekly Grind` and tap **Add**

It’ll launch like a native app — no browser chrome, full screen.

-----

## 📱 iOS Reminders

Daily 5:00 AM CDT reminders are set up via the iOS Reminders app, one for each workout day. Each reminder includes the full exercise list in its notes so you know exactly what’s coming before your feet hit the floor.

|Time       |Reminder                           |
|-----------|-----------------------------------|
|Mon 5:00 AM|💪 Workout Day: Shoulders & Core    |
|Tue 5:00 AM|💪 Workout Day: Back & Biceps       |
|Wed 5:00 AM|💪 Workout Day: Legs                |
|Thu 5:00 AM|💪 Workout Day: Arms, Core & Running|
|Fri 5:00 AM|💪 Workout Day: Chest & Triceps     |

-----

## 🗂 File Structure

```
weekly-grind/
└── workout-tracker.html   # The entire app — one file
└── README.md
```

No node_modules. No package.json. No build pipeline. Just open and go.

-----

## 🎨 Design

- **Theme:** Deep navy + steel blue on dark slate
- **Typography:** Bebas Neue (display) + DM Sans (body)
- **Aesthetic:** Athletic, focused, no distractions
- **Responsive:** Scales cleanly from 320px to desktop

-----

## ⚙️ How Auto-Reset Works

The tracker checks the current date every 60 seconds. If it detects that:

1. The saved `weekStart` doesn’t match the current Monday, **and**
1. It is Monday and the time is **≥ 5:00 AM CDT**

…it automatically resets all progress and starts a fresh week. No manual action needed.

-----

## 🙏 Philosophy

> *“Whatever you do, work at it with all your heart.”* — Colossians 3:23

This tracker is built around consistency, not perfection. Show up, check the boxes, walk with the Lord, and run the mile. Week by week.

-----

## 📄 License

MIT — use it, fork it, make it yours.
