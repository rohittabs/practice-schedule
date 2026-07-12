# Practice Schedule 🎸

> **Your practice thingy.** A free, beautiful practice tracker app for guitar and ukulele students.

Built by a music teacher, for music students. No accounts, no subscriptions, no app store. Just one file that works on every device.

---

## What is this?

Practice Schedule is a web app that lives in a single HTML file. Students open a link in their browser, add it to their home screen like a real app, and use it every day to track their practice. All data is saved privately on their own device.

**Live link:** https://practiseschedule.netlify.app

---

## What the app can do

| Feature | Details |
|---|---|
| **Practice plan** | Build a weekly routine with named items, categories, target minutes, and chosen days |
| **Today view** | See only what is planned for today, with a progress bar and streak counter |
| **Quick tick** | Tap the check to log the full target in one tap. Tap again to undo |
| **Timer** | Built-in stopwatch that auto-stops at the target time with a celebration screen |
| **Free logging** | Log any session not on the plan, with mood, notes, and backdating |
| **Categories** | 11 built-in color categories. Add, rename, recolor, or delete your own |
| **Progress charts** | 30-day line chart, 8-week bar chart, category breakdown, 12-week heatmap |
| **Streak tracking** | Daily streak with a grace-day system so one missed day does not break a long streak |
| **Weekly goal ring** | Visual ring showing progress toward the weekly minute target |
| **9 achievement badges** | Unlockable badges for milestones like first session, 7-day streak, 10 hours total, and more |
| **Day-complete party** | Confetti celebration when all items for the day are done |
| **Teacher summary** | One-tap copy of a WhatsApp-formatted bold summary to send the teacher |
| **Light and dark mode** | Manual toggle, starts in light mode |
| **Backup and restore** | Download a JSON rescue file. Restore it on any device |
| **Swipe actions** | Swipe left (touch) or drag left (mouse) to edit or undo any row |
| **Session history** | Browse, edit, or delete every past session. Deleting recalculates all totals |

---

## The 11 default categories

Warm-up, Chords, Scales, Strumming, Songs, Technique, Theory, Ear training, Exam prep, Sight Reading, Harmony

Students can add their own and delete any they do not need.

---

## The 9 achievement badges

| Badge | How to unlock |
|---|---|
| First note | Log your first session |
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
README.md        ← this file (instructions for you, the teacher)
index.html       ← the entire app, one self-contained file
```

That is it. The whole app is one file. No server, no database, no build steps.

---

## How to update the app

When a new version of `index.html` is available:

1. Come back to this repository on GitHub
2. Click **Add file** then **Upload files**
3. Upload the new `index.html`
4. Click the green **Commit changes** button

GitHub replaces the old file. The link stays the same. Students get the update the next time they open the app.

---

## How students install it on their device

Share this link with them: **https://yourusername.github.io/practice-schedule**

(Replace `yourusername` with your GitHub username and `practice-schedule` with whatever you named the repository.)

### iPhone or iPad

1. Open **Safari** (must be Safari, not Chrome, for the Add to Home Screen option)
2. Type the link in the address bar and tap Go
3. Tap the **Share button** (square with an arrow pointing up, in the bottom bar)
4. Scroll down and tap **Add to Home Screen**
5. Tap **Add** in the top right corner
6. The app icon appears on the home screen. Always open it from there

> **Important:** always use the home screen icon, not Safari directly. The home screen version saves data reliably. Opening from Safari can sometimes forget data.

### Android phone or tablet

1. Open **Chrome**
2. Type the link in the address bar and tap the arrow
3. Tap the **three dots** in the top right corner
4. Tap **Add to Home screen** (some phones say **Install app**)
5. Tap **Add** or **Install**
6. The app icon appears on the home screen. Always open it from there

### Windows computer or laptop

1. Open **Chrome** or **Edge**
2. Type the link and press Enter
3. Look for a small **install icon** (a monitor with a down arrow) at the right end of the address bar
4. Click it and click **Install**
5. The app opens in its own window with its own taskbar icon, like a real program
6. Alternatively press **Ctrl + D** to bookmark it

### Mac computer or laptop

1. Open **Safari**
2. Type the link and press Return
3. Click **File** in the menu bar, then **Add to Dock**
4. The app icon appears in your Dock
5. In **Chrome**: press **Cmd + D** to bookmark, or use the install icon in the address bar

---

## How students use the app

### First time setup

1. Type your name
2. Tap your instrument: Guitar or Ukulele
3. Set your weekly practice goal in minutes (150 is about 20 to 25 minutes a day)
4. Tap **Start planning**

### The Plan tab (build your routine here first)

- Tap **+ Add practice item**
- Give it a name, pick a category color, set target minutes, choose days of the week
- Tap **Add to plan**
- Edit or remove any item by tapping **Edit** next to it
- Scroll down to manage **Categories** and set your **Weekly goal**

### The Today tab (use this every day)

- See everything planned for today with a progress bar at the top
- Tap the **tick circle** to log the full target instantly. Tap the green tick again to undo
- Tap the **clock icon** to use the built-in timer. It stops automatically at the target time
- Swipe any row left (or drag with the mouse) to reveal **Edit** and **Undo** buttons
- Tap **+ Log a session** for anything not on the plan

### The Progress tab

- Streak counter, weekly goal ring, 30-day chart, 8-week bar chart
- Category breakdown showing where time goes
- 12-week consistency heatmap
- 9 unlockable achievement badges

### The More tab

- **Show** session history: browse, edit, or delete any past session
- **Download backup file**: saves a rescue copy as a JSON file. Do this every week
- **Restore from backup**: brings everything back after a new phone or accidental data loss
- **Copy summary for my teacher**: copies a formatted WhatsApp report with bold headings

---

## Data and privacy

- All practice data is stored only on the student's own device
- Nothing is sent to any server
- The teacher never sees the data unless the student shares the summary
- Clearing browser data or cache will erase the app data, which is why weekly backups are important

---

## Frequently asked questions

**The app forgot my data after I updated my phone.**
Use Restore from backup in the More tab with the last backup file. This is why weekly backups matter.

**A student tapped the tick by mistake.**
Tap the green tick again to undo it. The minutes are removed.

**I want to move data from one device to another.**
Download the backup file on the old device. Open the app on the new device. Go to More, tap Restore from backup, and pick the file.

**The app looks blank or broken on iPhone.**
This usually means it was opened from a file preview rather than a browser. Open Safari, type the link, and use Add to Home Screen.

**Does it work without internet?**
Yes, once the icon is on the home screen. The app runs fully offline after the first load.

**Can two students share one device?**
No, the app is designed for one student per device. Each device has its own separate data.

---

## Technical details (for the curious)

- Single self-contained HTML file, approximately 218 KB
- No external dependencies, no frameworks, no npm, no build process
- All charts are hand-drawn SVG, no chart libraries
- Data stored in the browser's localStorage
- Works as a Progressive Web App (PWA): installable on all major platforms
- Tested with 117 automated tests (46 logic tests, 71 end-to-end tests)
- Compatible with Chrome, Edge, Safari, and Firefox on all platforms

---

## Repository setup steps (for the teacher, one time only)

If you are reading this and have not set up the GitHub repository yet, here is how:

1. Go to **github.com** and sign in
2. Click **+** at the top right, then **New repository**
3. Name it `practice-schedule` (or anything you like)
4. Set it to **Public**
5. Check **Add a README file**
6. Click **Create repository**
7. Click **Add file**, then **Upload files**
8. Upload `index.html` from your computer
9. Click the green **Commit changes** button
10. Click **Settings** at the top of the repository
11. In the left sidebar click **Pages**
12. Under Branch, change **None** to **main** and click **Save**
13. Wait about 60 seconds, then refresh the page
14. GitHub shows your live link: `https://yourusername.github.io/practice-schedule`

Share that link with your students. You are done.

---

*Made with love for music students everywhere.*
