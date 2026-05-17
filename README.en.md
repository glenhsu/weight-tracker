# 💪 Solo Level Up V2.0 — Workout Tracker

> **Your data stays on your phone. No sign-up, no upload, no internet needed.**  
> Open in your browser and go. Close the tab and your data stays.

---

## Why You Need This

Most fitness apps want your email, your data, your money — and they upload everything to the cloud.

**Solo Level Up** does the opposite. Your data never leaves your phone. No servers, no backend, no one can peek at your workout history.

## Features

| Feature | Description |
|---------|-------------|
| 🏋️ **Templates** | Build your own workout plans. Exercise name, reps, and weight in separate fields — add, edit, delete, and save |
| ▶️ **Start Workout** | Run through your template, check off sets as you go, auto-calculates 1RM |
| ⏱ **Rest Timer** | Built-in countdown with beeps at 3 seconds and an alarm when time's up |
| 📊 **PR Leaderboard** | Automatically tracks your best 1RM for each exercise. Syncs instantly when workouts are deleted |
| 📋 **History** | Complete workout log by date. Wrong entry? Delete it with one tap |
| ⚙️ **Settings** | Custom rest seconds, dark theme UI |

## Quick Start

1. Open `index.html` on your phone's Chrome or Safari
2. Create a workout template (e.g., Chest Day)
3. Add exercises (e.g., Bench Press 60kg×10, Dumbbell Fly 20kg×12)
4. Tap **Start Workout** and go!
5. Check off completed sets — rest timer starts automatically

> 💡 **Pro tip**: On iOS, use Safari's "Add to Home Screen" to make it a standalone app — full screen, no URL bar.

## Tech Highlights

- **Single HTML file** — no framework, no backend, no dependencies
- **localStorage** — all data stays on-device. Back up before clearing browser data
- **Web Audio API** — native browser beeps, no audio files needed
- **1RM formula**: `weight × (1 + reps / 30)`
- **Mobile-first** — fills your screen, hides URL bar, handles rotation

## Privacy Promise

```
✅ Zero backend servers
✅ Zero account registration
✅ Zero data upload
✅ Zero ads
✅ Zero trackers
❌ We don't collect anything
```

Your workout data lives in your phone's localStorage. Even the developer can't see it.

## Who Is This For?

- Privacy-conscious lifters who don't want their gym data in the cloud
- Practical people who don't want another subscription
- Minimalists who just need a set counter and rest timer
- Cross-device users — drop the HTML in iCloud/Google Drive and access from anywhere

## Backup

Since data only lives on your phone, back it up regularly:

```js
// Chrome DevTools → Application → Local Storage → gym_v5_db
// Copy all → paste to a text file → save
```

Or just copy the `index.html` file to your cloud drive.

---

**Made with ❤️ by Hsu Glen**  
[GitHub](https://github.com/glenhsu/weight-tracker) | Issues & feedback welcome

> *"Solo Level Up" — Your workout, your data, your business.*