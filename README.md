from pathlib import Path

readme = """# ⏳ Countdown Ultra

A modern Arabic countdown timer with a glassmorphism UI, animated background, particles, progress indicators, and a live countdown.

## ✨ Features

- Live countdown showing:
  - Days
  - Hours
  - Minutes
  - Seconds
- Animated circular progress indicator
- Linear progress bar with percentage
- Animated particle background
- Aurora-style animated background
- Glassmorphism cards
- Responsive design for desktop and mobile
- Arabic RTL interface
- Smooth animations and transitions
- No external JavaScript frameworks required

## 📅 Countdown Date

The current countdown starts from:

**19 August 2026**

and ends on:

**11 March 2026**

> Note: The end date is configured directly inside the JavaScript code.

## 🚀 How to Run

No installation is required.

1. Download or clone the project.
2. Open `countdown_11-03-2026.html` in any modern web browser.
3. The countdown will start automatically.

## ⚙️ Changing the Countdown Date

Open the HTML file and find the configuration section:

```javascript
const START_DATE = new Date('2026-08-19T00:00:00');
const END_DATE = new Date('2026-03-11T00:00:00');
