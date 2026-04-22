[README.md](https://github.com/user-attachments/files/26982609/README.md)
# PMP Quest — Certification Journey

A gamified, interactive PMP (Project Management Professional) study companion that turns your 4-week exam prep into an engaging quest. Complete tasks, earn XP, build streaks, unlock achievements, and level up as you master project management concepts.

![PMP Quest Preview](https://img.shields.io/badge/PMP%20Exam%20Prep-Gamified-7c6af7?style=flat-square)
![Exam Format](https://img.shields.io/badge/Format-PMBOK%207%20%2F%20Current-4da6ff?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-2dd4a0?style=flat-square)

---

## 🎮 What is PMP Quest?

PMP Quest is a **fully offline, browser-based study game** designed for intermediate project managers preparing for the PMP certification exam. It combines:

- **Personalized 4-week study plan** aligned with the PMI Exam Content Outline (ECO)
- **XP & leveling system** — earn XP for tasks, quizzes, and daily streaks
- **Daily streaks with 7-star tracker** — +10 XP per day, +100 XP for 7-day weeks
- **Mini-quizzes** — 5 randomized PMP-style scenario questions per day
- **Dynamic deadline picker** — set your exam date and auto-adjust pacing
- **Achievement system** — 8 badges to unlock as you progress
- **Persistent progress** — all data saved locally in your browser

Perfect for learners who want **accountability, motivation, and structure** without expensive bootcamps.

---

## ✨ Key Features

### 📅 Dynamic Deadline
- **Click the deadline badge** at the top to set your exam date
- **Calendar picker** with native date input
- **Automatic pacing advice** based on days remaining
- **Format detection** — warns if your exam is after July 8, 2026 (new PMBOK 8 format)
- **Countdown display** — shows exact days, weeks, and required daily task pace

### 🎯 Gamification
| Feature | Details |
|---------|---------|
| **XP System** | Earn XP per task + daily bonuses + milestone multipliers |
| **Leveling** | 8 levels from Initiate → PMP Ready |
| **Streaks** | Track consecutive active days; 7-day weeks unlock +100 XP bonus |
| **Stars** | Visual 7-star tracker under streak counter |
| **Achievements** | 8 unlockable badges (First Step, Week Completions, Grinder, etc.) |
| **Toasts** | Celebratory popups for milestones |

### 📚 Study Structure
- **4-week plan** broken into 28 daily lessons
- **Per-day checklists** with specific topics and task counts
- **Review loops** — guidance on how to reinforce learning
- **Resource links** — curated free study materials (PMBOK 7, YouTube, practice questions)
- **Verification tests** — direct links to external quiz platforms to check understanding

### 🌐 100% Offline
- No internet required after first load
- All progress saved locally in your browser
- Single HTML file — no installation, no dependencies
- Works on desktop, tablet, or mobile

---

## 🚀 Getting Started

### Option 1: Download & Run Locally (Instant)
1. Download `pmp_quest.html` from this repository
2. Save it anywhere on your computer (Desktop, Documents, etc.)
3. Double-click the file — it opens in your default browser
4. Bookmark it for easy access

**That's it.** No setup, no internet required.

### Option 2: Share with a Team (GitHub Pages)
1. Fork or clone this repository
2. Enable GitHub Pages in repository Settings
3. Deploy from the `main` branch
4. Share the live URL: `https://yourusername.github.io/pmp-quest/`
5. Team members access via link — progress saves locally on each person's device

### Option 3: Share via Email/Drive
- Email `pmp_quest.html` directly to team members
- Or upload to Google Drive, OneDrive, Dropbox for easy sharing
- Works anywhere — no special permissions needed

---

## 🎓 Study Plan Overview

### **Week 1: Foundations & Exam Structure** (Days 1–7)
- Understand the PMP Exam Content Outline (ECO)
- Learn the 3 domains: People (42%), Process (50%), Business Environment (8%)
- Master PMBOK 7 principles and 8 performance domains
- Deep dive into Stakeholder, Team, and Planning domains
- **Goal:** Score 70%+ on 30-question Day 7 quiz

### **Week 2: Predictive PM Deep Dive** (Days 8–14)
- Scope, schedule, and cost management (EVM formulas)
- Risk, quality, and procurement management
- Integration and communications
- **Goal:** Score 70%+ on 50-question Day 14 mock exam

### **Week 3: Agile & Hybrid** (Days 15–21)
- Agile Manifesto values and principles
- Scrum, Kanban, XP, and SAFe frameworks
- Hybrid project lifecycle selection
- Leadership, conflict resolution, and team development (42% of the exam!)
- **Goal:** Score 70%+ on 50-question Day 21 agile-focused mock

### **Week 4: Final Boss — Full Mocks & Polish** (Days 22–28)
- Two full 180-question timed mock exams
- Targeted gap closure on weak areas
- Formula drills and final review
- Rest and exam day prep
- **Goal:** Score 75%+ on both full mocks

---

## 💾 How Progress is Saved

All data is saved automatically and locally using **browser localStorage**:

- ✅ **Automatic saves** — every task, setting, and quiz result saves instantly
- ✅ **Persistent across sessions** — close the browser, reopen the file, progress is still there
- ✅ **Private** — data never leaves your computer, no cloud sync
- ✅ **Survives crashes** — even if your browser crashes, progress is safe
- ❌ **Clears on data wipe** — if you clear browser cache/cookies, progress is erased

### Backing Up Your Progress
To save a backup of your progress:
1. Open DevTools (F12 or right-click → Inspect)
2. Go to **Application → Local Storage → File://**
3. Find key `pmpq_v2` and copy its value
4. Paste into a text file and save it somewhere safe

To restore from backup:
1. Open DevTools → Application → Local Storage
2. Create a new entry with key `pmpq_v2`
3. Paste your backed-up value

---

## 🎯 Settings & Customization

### In-Game Settings
- **Sound effects** — toggle sounds on/off for notifications
- **Show XP on tasks** — toggle XP values displayed on each task
- **Reset progress** — wipe all data and start fresh (irreversible)

### Personalization
- **Set your exam date** — dynamic deadline picker adapts the entire plan
- **Choose your week focus** — click week tabs to jump to any section
- **Expand/collapse days** — show only what you're studying today

---

## 📊 Scoring & Goals

### XP Breakdown
- **Task completion** — 100–200 XP per day (split across tasks)
- **Daily login** — +10 XP for first task of each day
- **7-day streak** — +100 XP bonus when you hit 7 consecutive active days
- **Quiz scores** — +bonus XP based on quiz performance (up to 50 XP per quiz)

### Example XP Path
- **Day 1–6:** 6 days × 10 XP (login) + task XP = ~900 XP
- **Day 7:** 10 XP (login) + 100 XP (7-day bonus) + task XP + quiz bonus = ~350 XP total Week 1
- Reach Level 3 (Practitioner) by mid-week 2

### Level Progression
| Level | XP Threshold | Title |
|-------|--------------|-------|
| 1 | 0 | Initiate |
| 2 | 200 | Apprentice |
| 3 | 450 | Practitioner |
| 4 | 750 | Specialist |
| 5 | 1,100 | Manager |
| 6 | 1,500 | Expert |
| 7 | 1,950 | Senior PM |
| 8 | 2,400 | PMP Ready |

---

## 🏆 Achievements

Unlock 8 badges as you progress:

| Badge | Condition |
|-------|-----------|
| ⚡ **First Step** | Complete your first task |
| 📖 **Week 1 Done** | Complete all 28 Week 1 tasks |
| 📊 **EVM Master** | Complete all Week 2 tasks |
| 🌀 **Agile Mindset** | Complete all Week 3 tasks |
| 🔥 **Grinder** | Complete 30 tasks total |
| 🏔 **Halfway There** | Reach 50% overall completion |
| 🎯 **All Done** | Complete every task (56/56) |
| ⏱ **Focused** | Complete 10 tasks in one session |

---

## 📚 Free Study Resources Included

The game includes **direct links** to these free resources:

### Official PMI Materials
- **PMI Exam Content Outline (ECO)** — Your exam blueprint
- **PMBOK 7th Edition** — Free for PMI members
- **Agile Practice Guide** — Free for PMI members

### Free Practice Questions
- **PMI Study Hall** — 175 free questions from PMI
- **PMPracticeExam.org** — 10 full free mock exams
- **PMP Exam For Free** — 700 aligned questions
- **Oliver Lehmann's 100 Hard Questions** — Challenging, well-explained
- **ExamTopics** — Crowd-sourced Q&A with community explanations
- **PrepCast** — 120 free timed questions

### YouTube Channels
- **PMPwithRay** — First-attempt coaching
- **David McLachlan** — PMP, ACP, Agile specialist
- **Simplilearn** — Full 2026-updated PMP playlist

---

## ⚠️ Important Notes

### Exam Deadline Update (July 8, 2026)
- **Current exam format** (PMBOK 7): Valid through July 8, 2026
- **New exam format** (PMBOK 8): Launches July 9, 2026
- **This plan covers:** Current PMBOK 7 format
- **If your exam is after July 8, 2026:** Supplement with PMI's updated materials on AI, sustainability, and value delivery

PMP Quest will remind you of this when you set your exam date.

### Time & Pacing
- **Designed for:** 1–2 hours per day over 4 weeks
- **Adjustment:** The game auto-calculates daily pace based on your deadline
- **Flexibility:** Slower pace? The plan still works; adjust your deadline accordingly
- **Intensity:** Fewer than 14 days until exam? The game switches to "crunch mode" and suggests prioritizing Week 4 (mocks + review)

### For Teams
- **Each person's progress is private** — saved only on their local browser
- **No built-in leaderboard** — but you can create a shared Google Sheet to track team progress
- **Accountability:** Share daily screenshots in Slack/Discord for motivation

---

## 🛠️ Technical Details

### What You Need
- A modern web browser (Chrome, Firefox, Safari, Edge)
- ~70 KB of disk space
- No internet required after opening the file

### Browser Compatibility
- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### How It Works
- **Single HTML file** — no build step, no dependencies
- **Vanilla JavaScript** — no frameworks, just pure JS
- **localStorage API** — persistent client-side storage
- **Responsive design** — works on desktop, tablet, mobile

### Privacy
- **All data is local** — nothing is sent to servers or tracked
- **No analytics** — your progress is yours alone
- **No cookies** — except localStorage for persistence

---

## 🚀 How to Share with Your Team

### Quick Share (Email)
```
Subject: PMP Exam Study Game — PMP Quest
Body: 
Hi team,

I found (created) this awesome gamified PMP study tool. You can 
start right now — just download the file and open it in any browser.

Your progress saves automatically on your computer.

Download: [pmp_quest.html link]
```

### Team Link (GitHub Pages)
1. Upload `pmp_quest.html` to a public GitHub repo
2. Enable GitHub Pages in Settings
3. Share: `https://yourusername.github.io/pmp-quest/`

### Team Leaderboard (Optional)
Create a shared Google Sheet for weekly check-ins:
```
Name | Week | Tasks Done | Level | Streak | Total XP
---
Alice | 1 | 28 | 2 | 5 | 450
Bob | 1 | 15 | 1 | 2 | 210
```

---

## 📖 Tips for Success

### Daily Routine
1. **Open the game** and expand today's lesson
2. **Read the checklist** and complete tasks in order
3. **Do the review loop** — reinforce the material
4. **Click study material links** to read/watch content
5. **Take the mini-quiz** at the end of the day
6. **Check off all tasks** — this locks in your daily +10 XP

### Week 1–3
- **Read before practicing** — understand concepts before answering questions
- **Log wrong answers** — write them in a notebook to review later
- **Target 70%+ on quizzes** — before moving to the next day

### Week 4
- **Full 180-question mocks** — simulate real exam conditions (230 minutes, timed)
- **Review diagnostics** — which domains are you weak in?
- **Focus > breadth** — the last 2 days, deep-dive your weakest area only
- **Sleep 8+ hours** — memory consolidates during sleep

### Exam Day
- **Flag uncertain questions** — never spend >2 minutes on one
- **Read question stems from the end first** — identify what's being asked
- **Your first instinct is usually right** — only change answers with a clear reason
- **Trust the prep** — you've got this

---

## ❓ FAQ

**Q: Will this guarantee I pass the exam?**
A: No guarantee, but the plan is comprehensive and exam-aligned. Success depends on consistent effort, quality study, and real understanding (not memorization).

**Q: Can I take this at my own pace?**
A: Yes. The plan assumes 4 weeks, but you can speed up or slow down. Set your deadline accordingly.

**Q: What if I skip a day?**
A: Your streak resets the next time you're inactive for >24 hours. The game tracks this automatically.

**Q: Do I need an internet connection?**
A: No. After opening the file once, it works completely offline. Study anywhere.

**Q: Where does my data go?**
A: Nowhere. It stays on your computer in your browser's localStorage. No tracking, no cloud sync.

**Q: Can I share my progress with teammates?**
A: Your progress is local to your browser. You can screenshot stats or manually log them in a shared sheet. No automatic sync.

**Q: What if I clear my browser cache?**
A: All progress is erased. Back up your progress data (see "Backing Up" section above) if you're worried.

**Q: Is there a mobile app?**
A: Not yet, but the web version is fully responsive and works great on mobile browsers.

**Q: Can I contribute or suggest features?**
A: Feedback is always welcome! Open an issue on the repo or fork and submit a PR.

---

## 📝 License

This project is provided as-is for educational purposes. PMP and PMBOK are registered trademarks of the Project Management Institute. This is an independent study tool, not affiliated with PMI.

---

## 🎓 About This Tool

**Created for:** Intermediate project managers preparing for PMP certification
**Exam Format:** PMBOK 7th Edition (current through July 8, 2026)
**Study Duration:** 4 weeks, 1–2 hours/day
**Total Tasks:** 56 daily lessons across 4 weeks
**Total XP Available:** ~2,400+ XP

---

## 🙌 Get Started Now

1. **Download** `pmp_quest.html`
2. **Open** in your browser
3. **Set your exam date** (click the deadline badge)
4. **Start Day 1** — read the topics, complete the checklist
5. **Build your streak** — 7 days = +100 XP bonus
6. **Level up** → unlock achievements → pass the exam

**Good luck, PM! You got this.** 🚀

---

## 📧 Questions or Issues?

- Found a bug? Open an issue on GitHub
- Want to suggest a feature? Submit a pull request
- Want to share your success? Drop a star ⭐

---

**Version:** 1.0 | **Last Updated:** April 2026 | **Status:** Complete & Production-Ready
