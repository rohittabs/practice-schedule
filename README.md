# Cadence 🎸

> **Simply Practice.**

A free practice tracker for guitar and ukulele. No accounts, no subscriptions, no app store. Just one file that works on every device.

---

## What is this?

Cadence is a web app that lives in a single HTML file. Open a link in a browser, add it to a home screen like a real app, and use it every day to track practice. All data is saved privately on that device only, nothing is ever sent anywhere.

**Live link:** https://rohittabs.github.io/cadence

---

## What the app can do

| Feature | Details |
|---|---|
| **Practice plan** | Build a routine with named items, categories, target minutes, and chosen days. Starts empty on purpose, so the plan is built first, then practiced |
| **Today view** | See only what is planned for today, with a progress bar and streak counter |
| **Log a session** | Tapping the tick opens a quick sheet (target prefilled, editable) with a mood picker and an optional note, then saves it. Tapping an already-logged green tick undoes it instantly |
| **Timer** | Built-in stopwatch that auto-stops the moment the target time is reached, celebrates, and offers **Finish and log** or **Continue practicing**. Continuing keeps the clock running and logs the real elapsed time whenever it is finished |
| **Metronome** | A simple BPM-only metronome (40 to 240 bpm) appears inside the practice timer. One continuous click, no accents, no beat or time-signature settings. Drag the slider or use the plus/minus buttons to change tempo |
| **Extra practice** | Log anything beyond the plan for today. It gets its own name, category, and target minutes, shows inline in the Today list with an EXTRA tag, and gets its own timer and tick, just like a routine item. Removing an extra also removes any minutes already logged for it that day |
| **Categories** | 11 built-in color categories. Add, rename, recolor, or delete any of them from the Plan tab. Deleting a category that a plan item still uses is blocked until that item is reassigned |
| **Progress charts** | 30-day line chart, 8-week bar chart, category breakdown, 12-week heatmap |
| **Streak tracking** | Daily streak with a grace-day system so one missed day does not break a long streak |
| **Weekly goal ring** | Visual ring showing progress toward the weekly minute target |
| **9 achievement badges** | Unlockable badges for milestones like first session, 7-day streak, 10 hours total, and more |
| **Day-complete celebration** | Confetti and a trophy card appear once the whole day's plan and any extras are finished |
| **Copy summary** | One-tap copy of a WhatsApp-formatted bold summary, ready to paste and send anywhere |
| **Appearance** | A dedicated Light, Dark, and System picker in the More tab. System follows the device's own setting automatically. Opens in Light by default until changed |
| **Backup and restore** | Download a JSON rescue file. Restore it on any device |
| **Swipe actions** | Swipe left (touch) or drag left (mouse) to edit, undo, or remove any row |
| **Session history** | Browse, edit, or delete every past session. Deleting recalculates all totals |
| **Adaptive layout** | Automatically rearranges into a full-width, multi-column layout on tablets and laptops in any orientation, and stays single-column on phones |

---

## The 11 default categories

Warm-up, Chords, Scales, Strumming, Songs, Technique, Theory, Ear training, Exam prep, Sight Reading, Harmony

New categories can be added at any time, and any unused category can be renamed, recolored, or deleted.

---

## The 9 achievement badges

| Badge | How to unlock |
|---|---|
| First note | Log a first session |
| 7-day streak | Practice 7 days in a row |
| 30-day streak | Practice 30 days in a row |
| 10 hours | Reach 600 total minutes |
| 50 hours | Reach 3000 total minutes |
| Century | Log 100 sessions |
| All-rounder | Practice across 5 different categories |
| Goal week | Hit the weekly minute goal at least once |
| Committed | Practice on 20 different days |

---

## Files in this repository

```
README.md        ← this file
index.html       ← the entire app, one self-contained file
```

That is it. The whole app is one file. No server, no database, no build steps.

---

## How to install

Open this link in a browser: **https://rohittabs.github.io/cadence**

Any modern browser works. Below are exact steps for the two most common browsers on every kind of device, so pick whichever is already installed.

### iPhone or iPad

**Safari (recommended, most reliable for saving data long term):**
1. Open **Safari** and go to the link above
2. Tap the **Share button** (the square with an arrow pointing up, in the bottom toolbar; on iPad it is in the top toolbar)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add** in the top right corner
5. An app icon named **Cadence** appears on the home screen. Always open the app from this icon afterward, not from a browser tab

**Chrome on iOS:**
1. Open **Chrome** and go to the link above
2. Tap the **Share icon** at the top of the screen
3. Tap **Add to Home Screen**
4. Tap **Add**

> If anything ever looks like it forgot data after using Chrome on iOS, reopen through the Safari version instead. Safari's home screen storage is the most dependable on iOS.

### Android phone or tablet

**Chrome (default on most Android devices):**
1. Open **Chrome** and go to the link above
2. Tap the **three dots** in the top right corner
3. Tap **Add to Home screen** (some phones show **Install app** instead)
4. Tap **Add** or **Install**
5. An app icon appears on the home screen

**Samsung Internet or other Android browsers:**
Most Android browsers have a similar option, usually called **Add to Home screen** or **Install app**, found in the browser's menu (often three dots or three lines).

### Windows computer or laptop

**Chrome:**
1. Open **Chrome** and go to the link above
2. Look for a small **install icon** (a monitor with a down arrow) at the right end of the address bar
3. Click it, then click **Install**
4. The app opens in its own window with its own taskbar icon, like a regular program

**Edge (built into Windows):**
1. Open **Edge** and go to the link above
2. Click the **three dots** menu, then **Apps**, then **Install this site as an app**
3. Click **Install**

**Firefox:**
Firefox does not support installing sites as standalone apps. Bookmark the page instead: press **Ctrl + D**.

Bookmarking works in any browser: press **Ctrl + D** for a quick shortcut without installing.

### Mac computer or laptop

**Safari:**
1. Open **Safari** and go to the link above
2. Click **File** in the menu bar, then **Add to Dock**
3. An app icon appears in the Dock

**Chrome:**
1. Open **Chrome** and go to the link above
2. Click the **install icon** in the address bar, or open the three-dot menu, then **Cast, save, and share**, then **Install page as app**
3. Click **Install**

Bookmarking works too: press **Cmd + D** in either browser for a quick shortcut.

### Any other device with a modern browser

The link above works in any browser released in the last several years, including Chromebooks, Linux desktops, and smart displays with a browser. Installing as an app may not be available everywhere, but the app itself works normally, and bookmarking always works as a fallback.

---

## How to use the app

### First time setup

1. Type a name
2. Choose an instrument: Guitar or Ukulele
3. Set a weekly practice goal in minutes (150 is about 20 to 25 minutes a day)
4. Tap **Start planning**

### The Plan tab (build a routine here first)

- Tap **+ Add practice item**
- Give it a name, pick a category color, set target minutes, choose days of the week
- Tap **Add to plan**
- Edit or remove any item by tapping **Edit** next to it
- Scroll down to the **Categories** card to add, rename, recolor, or delete categories
- Set the **Weekly goal** at the bottom

The plan starts completely empty, on purpose. Build it before practicing.

### The Today tab (use this every day)

- See everything planned for today with a progress bar at the top
- Tap the **tick circle** to open a quick log sheet: minutes prefilled to the target, a mood picker, and an optional note. Save it to log. Tap an already-green tick again to undo instantly
- Tap the **clock icon** to use the built-in timer. It stops automatically the moment the target is reached, then offers **Finish and log** or **Continue practicing**
- Inside the timer, a **metronome** is available: set a tempo with the slider or the plus/minus buttons, and start or stop a single continuous click
- Tap **+ Log extra practice** for anything not on the plan. It gets added to today's list with an EXTRA tag, its own target, and its own timer
- Swipe any row left (or drag with the mouse on a laptop) to reveal **Edit**, **Undo**, or **Remove** buttons
- When everything for the day, including any extras, is finished, a confetti celebration appears

### The Progress tab

- Streak counter, weekly goal ring, 30-day chart, 8-week bar chart
- Category breakdown showing where time goes
- 12-week consistency heatmap
- 9 unlockable achievement badges

### The More tab

- **Appearance**: choose Light, Dark, or System. System follows the device's own light/dark setting automatically
- **Download backup file**: saves a rescue copy as a JSON file. Doing this regularly is a good habit
- **Restore from backup**: brings everything back after a new device or accidental data loss
- **Copy summary**: copies a formatted WhatsApp report with bold headings, ready to paste and send
- **Session history**: browse, edit, or delete any past session. Deleting recalculates all totals
- **Profile**: edit name and instrument, or erase all data

---

## Data and privacy

- All practice data is stored only on the device it is used on, in the browser's local storage
- Nothing is ever sent to a server
- Data is never seen by anyone else unless a summary is shared directly
- Clearing browser data or cache will erase the app data, which is why regular backups matter

---

## Frequently asked questions

**The app forgot the data after a device update.**
Use Restore from backup in the More tab with the last backup file. This is why regular backups matter.

**The tick was tapped by mistake.**
If it opened the log sheet, just cancel it. If it was already saved, tap the now-green tick again to undo, which removes the minutes.

**How to move data from one device to another.**
Download the backup file on the old device. Open the app on the new device. Go to More, tap Restore from backup, and pick the file.

**The app looks blank, dark, or broken in a preview or share sheet.**
That is normal for a quick file preview, which is not the real app. Open the actual link in a browser (Safari, Chrome, Edge) to see the app correctly, or open it from the installed home screen icon.

**Does it work without internet?**
Yes, once the icon is on the home screen. The app runs fully offline after the first load.

**Can two people share one device?**
No, the app is designed for one profile per device. Each device keeps its own separate data.

**How does Appearance: System work?**
It checks the device's own light or dark mode setting each time the app opens, and matches it automatically. Choosing Light or Dark instead locks the app to that look regardless of the device setting.

**Does the layout work on iPad and laptops?**
Yes. On any screen 760 pixels wide or larger, in either orientation, the app switches to a full-width, multi-column layout automatically. Phones stay single-column.

---

## Technical details

- Single self-contained HTML file, roughly 250 KB
- No external dependencies, no frameworks, no build process
- All charts are hand-drawn SVG, no charting libraries
- The metronome uses the Web Audio API for precise timing, with no audio files
- Every confirmation dialog (delete, erase, remove) is built into the app itself rather than relying on the browser's native popups, so it works reliably even inside restrictive webviews and previews
- Data stored in the browser's localStorage
- Works as a Progressive Web App (PWA): installable on all major platforms
- Tested with 195 automated tests (46 logic tests, 149 end-to-end tests)
- Compatible with Chrome, Edge, Safari, and Firefox on all platforms

---

## Version history

### v1.0 — current release
First public release under the Cadence name. Full practice planning, extra-practice logging, built-in timer with metronome, achievement badges, progress charts, appearance modes, backup and restore, and a fully adaptive layout for phones, tablets, and laptops.

---

*Simply Practice.*
