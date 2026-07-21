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
| **Metronome** | A simple BPM-only metronome (40 to 240 bpm) appears inside the practice timer. One continuous click, no accents, no beat or time-signature settings. Tap the number to type an exact tempo, or nudge it one beat at a time with the plus and minus buttons |
| **Extra practice** | Log anything beyond the plan for today. It gets its own name, category, and target minutes, shows inline in the Today list with an EXTRA tag, and gets its own timer and tick, just like a routine item. Removing an extra also removes any minutes already logged for it that day |
| **Repertoire (Songs)** | A dedicated tab for tracking songs. Each song has a stage (Learning, Polishing, Performance ready), a tempo goal you build up over time with a growth chart, and a checklist of sections that the player defines from scratch, nothing is assumed. A **Practice this today** button sends the song straight into today's list with its own timer and metronome |
| **Categories** | 12 built-in color categories, including Fingerstyle. Add, rename, recolor, or delete any of them from the Plan tab. Deleting a category that a plan item still uses is blocked until that item is reassigned |
| **Progress charts** | 30-day line chart, 8-week bar chart, category breakdown, 12-week heatmap |
| **Streak tracking** | Daily streak with a grace-day system so one missed day does not break a long streak |
| **Weekly goal ring** | Visual ring showing progress toward the weekly minute target |
| **9 achievement badges** | Unlockable badges for milestones like first session, 7-day streak, 10 hours total, and more |
| **Day-complete celebration** | Confetti and a trophy card appear once the whole day's plan and any extras are finished |
| **Copy summary** | One-tap copy of a WhatsApp-formatted summary with bold text and real bullet lists, covering practice minutes, streaks, category breakdown, and a full repertoire report, ready to paste and send anywhere |
| **Appearance** | A dedicated Light, Dark, and System picker in the More tab. System follows the device's own setting automatically. Opens in Light by default until changed |
| **Backup and restore** | Download a JSON rescue file. Restore it on any device |
| **Swipe actions** | Swipe left (touch) or drag left (mouse) to edit, undo, or remove any row |
| **Session history** | Browse, edit, or delete every past session. Deleting recalculates all totals |
| **Adaptive layout** | Automatically rearranges into a full-width, multi-column layout on tablets and laptops in any orientation, and stays single-column on phones |

---

## Repertoire, in detail

The Songs tab is the biggest addition since v1.0, and it is worth explaining how it thinks.

**Sections are never assumed.** A new song starts with zero sections. There is no automatic Intro, Verse, or Chorus. The player adds exactly the sections that make sense for that song, whether that is "Intro", "the solo", or "bar 32 where the stretch is". Each section can be renamed or removed at any time, and tapping one cycles it through To do, Working, and Done.

**Tempo tracking is optional and only counts once it is actually used.** A song's current and target tempo default to placeholder numbers, but they are not treated as real data until the player deliberately changes one. Once touched, every update is timestamped, building a growth chart with a dashed line marking the target speed. This means a song nobody has timed yet never reports a fake tempo to anyone.

**Progress is a stage the player controls, filled in by measurable work.** The percentage ring is not a blind average of ticked boxes. Instead, each stage sets a ceiling the ring cannot cross until the player promotes the song themselves:

- **Learning** fills from 0% up to 60%
- **Polishing** fills from 60% up to 90%
- **Performance ready** is always 100%

So finishing every section you have added to a song while it is still in Polishing shows 90%, not 100%, because the player has not yet said the song is ready to perform. A short note under the song's title always explains the number in plain words, for example "Polishing stage, 1 of 1 section done, tempo not tracked", and if all tracked work is finished but the stage has not been promoted, a message explains exactly what to do next.

**Practicing a song uses the existing engine.** The **Practice this today** button adds the song to today's list as extra practice, so the same timer, metronome, and minute logging that everything else in Cadence uses works for repertoire too, and those minutes are automatically counted toward that song's practiced time and session count.

---

## The 12 default categories

Warm-up, Chords, Scales, Strumming, Songs, Technique, Theory, Ear training, Exam prep, Sight Reading, Harmony, Fingerstyle

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

---

## First run

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
- Inside the timer, a **metronome** is available: tap the number to type an exact tempo, or use the plus and minus buttons to nudge it one beat at a time
- Tap **+ Log extra practice** for anything not on the plan. It gets added to today's list with an EXTRA tag, its own target, and its own timer
- Swipe any row left (or drag with the mouse on a laptop) to reveal **Edit**, **Undo**, or **Remove** buttons
- When everything for the day, including any extras, is finished, a confetti celebration appears

### The Songs tab

- Tap **+ Add a song** and give it a name and, optionally, an artist
- Choose a stage: Learning, Polishing, or Performance ready
- Tap the tempo numbers to type them in, or use the plus and minus buttons to nudge by one beat. Leave the target at 0 if speed is not being tracked yet
- Add sections with **+ Add section**, name them however makes sense, and tap them to cycle through To do, Working, and Done
- Use **Edit** next to the sections heading to rename or remove any section
- Tap **Practice this today** to send the song into today's practice list
- Open any song to see its tempo growth chart once a few readings exist, plus how many minutes and sessions have gone into it

### The Progress tab

- Streak counter, weekly goal ring, 30-day chart, 8-week bar chart
- Category breakdown showing where time goes
- 12-week consistency heatmap
- 9 unlockable achievement badges

### The More tab

- **Appearance**: choose Light, Dark, or System. System follows the device's own light/dark setting automatically
- **Download backup file**: saves a rescue copy as a JSON file. Doing this regularly is a good habit
- **Restore from backup**: brings everything back after a new device or accidental data loss
- **Copy summary**: copies a formatted WhatsApp report with bold headings, bullet lists, and a full repertoire section, ready to paste and send
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

**Why does a song show less than 100% even though every section is done?**
Because a stage caps how high the progress ring can go until the song is promoted. Learning caps at 60%, Polishing at 90%. A note under the song's title always explains the current number, and once all tracked work is finished, a message appears explaining that moving the song to the next stage will raise it.

**Does the layout work on iPad and laptops?**
Yes. On any screen 760 pixels wide or larger, in either orientation, the app switches to a full-width, multi-column layout automatically. Phones stay single-column.

---

## Technical details

- Single self-contained HTML file, roughly 354 KB
- No external dependencies, no frameworks, no build process
- All charts are hand-drawn SVG, no charting libraries
- The metronome uses the Web Audio API for precise timing, with no audio files
- Every confirmation dialog (delete, erase, remove) is built into the app itself rather than relying on the browser's native popups, so it works reliably even inside restrictive webviews and previews
- Data stored in the browser's localStorage
- Works as a Progressive Web App (PWA): installable on all major platforms
- Compatible with Chrome, Edge, Safari, and Firefox on all platforms

---

## Version history

### v2.0 (current release)
- Full visual redesign: refreshed color palette (a pink-to-purple gradient runs through the header, buttons, and progress bars), softer cards, and updated typography throughout every tab
- Added the **Repertoire (Songs)** tab: track songs with a tempo growth chart, user-defined sections, notes, and a staged progress model (Learning, Polishing, Performance ready) where the stage a player chooses caps the ring so nothing is marked finished until the player says so
- The teacher summary now includes a full repertoire report, sorted so songs needing work appear first, using WhatsApp's real bullet-list formatting
- Added a 12th default category, Fingerstyle
- Metronome and song tempo controls now step one beat at a time and accept a typed number directly, instead of jumping in fives
- Fixed a color variable that left "Polishing" status pills and "Working" section chips invisible in some cases
- Fixed the day timer's "Finish and log" not completing an item when tapped before the timer was started
- Fixed the More tab's action buttons becoming unclickable inside the wide-screen layout
- Fixed the practice data becoming invisible inside file previews and some restricted webviews by declaring the app's color scheme explicitly
- Replaced every native browser confirmation popup with one built into the app, since native popups are silently blocked in some webviews
- Adaptive layout now stretches to fill tablets and laptops in any orientation instead of floating in a narrow centered column

### v1.0
First public release under the Cadence name. Full practice planning, extra-practice logging, built-in timer with metronome, achievement badges, progress charts, appearance modes, backup and restore, and a fully adaptive layout for phones, tablets, and laptops.

---

*Simply Practice.*
