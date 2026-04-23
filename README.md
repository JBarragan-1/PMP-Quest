PMP Quest — Certification Journey
A gamified, interactive PMP (Project Management Professional) study companion that turns your 4-week exam prep into an engaging quest. Complete tasks, earn XP, build streaks, unlock achievements, and level up as you master project management concepts — powered by the official PMBOK 7 Guide built right into the game.
![PMP Quest Preview](https://img.shields.io/badge/PMP%20Exam%20Prep-Gamified-7c6af7?style=flat-square)
![Exam Format](https://img.shields.io/badge/Format-PMBOK%207%20%2F%20Current-4da6ff?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-2dd4a0?style=flat-square)
---
🎮 What is PMP Quest?
PMP Quest is a fully offline, browser-based study game designed for intermediate project managers preparing for the PMP certification exam. It combines:
The full PMBOK 7 Guide embedded right in the game — no purchase or PMI membership required
Personalized 4-week study plan aligned with the 8 Performance Domains and 12 Principles
XP & leveling system — earn XP for tasks, quizzes, and daily streaks
Daily streaks with 7-star tracker — +10 XP per day, +100 XP for 7-day weeks
Key terms from the PMBOK glossary highlighted in every domain
Mini-quizzes — 5 randomized PMP-style scenario questions per day
Dynamic deadline picker — set your exam date and auto-adjust pacing
Achievement system — 8 badges to unlock as you progress
Persistent progress — all data saved locally in your browser
---
📦 What You Need to Download
Two files, both in this repository:
`pmp_quest.html` — the game itself (89 KB)
`PMBOK7.pdf` — the official PMBOK 7 Guide (4.4 MB)
Both files must live in the same folder. The game loads the PDF directly from your disk (or GitHub Pages) into an in-game viewer — no external downloads, no paywall.
---
✨ Key Features
📅 Dynamic Deadline
Click the deadline badge at the top to set your exam date
Calendar picker with native date input
Automatic pacing advice based on days remaining
Format detection — warns if your exam is after July 8, 2026 (new PMBOK 8 format)
Countdown display — shows exact days, weeks, and required daily task pace
🎯 Gamification
Feature	Details
XP System	Earn XP per task + daily bonuses + milestone multipliers
Leveling	8 levels from Initiate → PMP Ready
Streaks	Track consecutive active days; 7-day weeks unlock +100 XP bonus
Stars	Visual 7-star tracker under streak counter
Achievements	8 unlockable badges (First Step, Week Completions, Grinder, etc.)
Toasts	Celebratory popups for milestones
📚 Study Structure
4-week plan broken into 28 daily lessons aligned to PMBOK 7
Per-day checklists with specific topics and task counts
Review loops — guidance on how to reinforce learning
Resource links — curated free study materials (PMBOK 7, YouTube, practice questions)
Verification tests — direct links to external quiz platforms to check understanding
🌐 100% Offline
No internet required after first load (including the PMBOK 7 PDF)
All progress saved locally in your browser
Works on desktop, tablet, or mobile
📖 In-Game PMBOK 7 Guide
The full 370-page PMBOK 7 Guide is embedded in the game
Click the "PMBOK 7 Guide" button in the header to open it in a modal viewer
No need to buy PMBOK or maintain a PMI membership
Read any section directly while studying — pages are referenced throughout the daily checklists
The PDF is loaded from the same folder as the HTML file
🔑 Key Terms Per Domain
Every day displays the key terms covered in that Performance Domain
Pulled directly from the PMBOK 7 glossary
Glanceable pill-style badges help you quickly identify vocabulary to master
---
🚀 Getting Started
Option 1: Download & Run Locally (Instant)
Download both `pmp_quest.html` and `PMBOK7.pdf` from this repository
Save them in the same folder on your computer (Desktop, Documents, etc.)
Double-click `pmp_quest.html` — it opens in your default browser
Click the "PMBOK 7 Guide" button at the top to read the full guide inside the game
Bookmark it for easy access
That's it. No setup, no internet required.
Option 2: Share with a Team (GitHub Pages)
Fork or clone this repository
Enable GitHub Pages in repository Settings (deploy from main branch)
Share the live URL: `https://yourusername.github.io/pmp-quest/pmp_quest.html`
Team members access via link — the PDF loads from the repo automatically
Each person's progress saves locally on their own device
Option 3: Share via Email/Drive
ZIP both files together and email to team members
Or upload both to Google Drive, OneDrive, or Dropbox in a shared folder
Team members download both to the same folder and open the HTML
---
🎓 Study Plan Overview
The plan maps directly to the 8 Performance Domains and 12 Principles from PMBOK 7. Every day references specific page ranges you can read in the in-game PDF viewer.
Week 1: Foundations & Principles (Days 1–7)
Read the PMI Exam Content Outline (free, no signup)
Master the 12 PM Principles from PMBOK 7 (pages 21–60)
Study the Value Delivery System and Stakeholder Performance Domain
Key domains covered: Stakeholder, Principles foundation
Goal: Score 70%+ on 30-question Day 7 quiz
Week 2: Team, Planning & Project Work (Days 8–14)
Team Performance Domain (pages 16–31): Tuckman, leadership styles, conflict modes
Planning Performance Domain (pages 51–68): WBS, critical path, EVM formulas
Project Work Domain (pages 69–79): procurement, change control
Key domains covered: Team, Planning, Project Work
Goal: Score 70%+ on 50-question Day 14 mock exam
Week 3: Delivery, Measurement & Uncertainty (Days 15–21)
Delivery + Development Approach domains (pages 32–92): agile, Scrum, predictive vs adaptive
Measurement Performance Domain (pages 93–115): KPIs, burn charts, CFDs
Uncertainty Performance Domain (pages 116–129): risk responses, EMV, Monte Carlo
Key domains covered: Delivery, Development Approach, Measurement, Uncertainty
Goal: Score 70%+ on 50-question Day 21 agile/risk mock
Week 4: Tailoring, Models & Final Mocks (Days 22–28)
Tailoring chapter (pages 131–152)
Models, Methods & Artifacts chapter (pages 153–196)
Two full 180-question timed mock exams
Formula drills and final review
Rest and exam day prep
Goal: Score 75%+ on both full mocks
---
💾 How Progress is Saved
All data is saved automatically and locally using browser localStorage:
✅ Automatic saves — every task, setting, and quiz result saves instantly
✅ Persistent across sessions — close the browser, reopen the file, progress is still there
✅ Private — data never leaves your computer, no cloud sync
✅ Survives crashes — even if your browser crashes, progress is safe
❌ Clears on data wipe — if you clear browser cache/cookies, progress is erased
Backing Up Your Progress
To save a backup of your progress:
Open DevTools (F12 or right-click → Inspect)
Go to Application → Local Storage → File://
Find key `pmpq_v2` and copy its value
Paste into a text file and save it somewhere safe
To restore from backup:
Open DevTools → Application → Local Storage
Create a new entry with key `pmpq_v2`
Paste your backed-up value
---
🎯 Settings & Customization
In-Game Settings
Sound effects — toggle sounds on/off for notifications
Show XP on tasks — toggle XP values displayed on each task
Reset progress — wipe all data and start fresh (irreversible)
Personalization
Set your exam date — dynamic deadline picker adapts the entire plan
Choose your week focus — click week tabs to jump to any section
Expand/collapse days — show only what you're studying today
---
📊 Scoring & Goals
XP Breakdown
Task completion — 100–200 XP per day (split across tasks)
Daily login — +10 XP for first task of each day
7-day streak — +100 XP bonus when you hit 7 consecutive active days
Quiz scores — +bonus XP based on quiz performance (up to 50 XP per quiz)
Example XP Path
Day 1–6: 6 days × 10 XP (login) + task XP = ~900 XP
Day 7: 10 XP (login) + 100 XP (7-day bonus) + task XP + quiz bonus = ~350 XP total Week 1
Reach Level 3 (Practitioner) by mid-week 2
Level Progression
Level	XP Threshold	Title
1	0	Initiate
2	200	Apprentice
3	450	Practitioner
4	750	Specialist
5	1,100	Manager
6	1,500	Expert
7	1,950	Senior PM
8	2,400	PMP Ready
---
🏆 Achievements
Unlock 8 badges as you progress:
Badge	Condition
⚡ First Step	Complete your first task
📖 Week 1 Done	Complete all 28 Week 1 tasks
📊 EVM Master	Complete all Week 2 tasks
🌀 Agile Mindset	Complete all Week 3 tasks
🔥 Grinder	Complete 30 tasks total
🏔 Halfway There	Reach 50% overall completion
🎯 All Done	Complete every task (90/90)
⏱ Focused	Complete 10 tasks in one session
---
📚 Free Study Resources Included
All links in the game have been vetted — no paywalls, no account signups required. The game includes direct links to these free resources:
Official PMI Materials (Free)
PMI Exam Content Outline (ECO) — Free PDF download, no signup
PMBOK 7th Edition — Included as a PDF in the game, no PMI membership required
Free Practice Questions (No Signup)
PMPracticeExam.org — 10 full free mock exams, no account needed
PMP Exam For Free — 700 aligned questions across 7 sets
Oliver Lehmann's 100 Hard Questions — Challenging and well-explained
ExamTopics — Crowd-sourced Q&A with community explanations
PrepCast — 120 free timed questions
Mometrix — Full free practice exam
Master of Project — Free Q&A blog with detailed explanations
YouTube Channels (Free)
PMPwithRay — First-attempt coaching
David McLachlan — PMP, ACP, Agile specialist
Simplilearn — Full 2026-updated PMP playlist
---
⚠️ Important Notes
Exam Deadline Update (July 8, 2026)
Current exam format (PMBOK 7): Valid through July 8, 2026
New exam format (PMBOK 8): Launches July 9, 2026
This plan covers: Current PMBOK 7 format
If your exam is after July 8, 2026: Supplement with PMI's updated materials on AI, sustainability, and value delivery
PMP Quest will remind you of this when you set your exam date.
Time & Pacing
Designed for: 1–2 hours per day over 4 weeks
Adjustment: The game auto-calculates daily pace based on your deadline
Flexibility: Slower pace? The plan still works; adjust your deadline accordingly
Intensity: Fewer than 14 days until exam? The game switches to "crunch mode" and suggests prioritizing Week 4 (mocks + review)
For Teams
Each person's progress is private — saved only on their local browser
No built-in leaderboard — but you can create a shared Google Sheet to track team progress
Accountability: Share daily screenshots in Slack/Discord for motivation
---
🛠️ Technical Details
What You Need
A modern web browser (Chrome, Firefox, Safari, Edge)
~70 KB of disk space
No internet required after opening the file
Browser Compatibility
✅ Chrome/Edge (Recommended)
✅ Firefox
✅ Safari
✅ Mobile browsers (iOS Safari, Chrome Mobile)
How It Works
Single HTML file — no build step, no dependencies
Vanilla JavaScript — no frameworks, just pure JS
localStorage API — persistent client-side storage
Responsive design — works on desktop, tablet, mobile
Privacy
All data is local — nothing is sent to servers or tracked
No analytics — your progress is yours alone
No cookies — except localStorage for persistence
---
🚀 How to Share with Your Team
Quick Share (Email)
```
Subject: PMP Exam Study Game — PMP Quest
Body: 
Hi team,

I found (created) this awesome gamified PMP study tool. You can 
start right now — just download the file and open it in any browser.

Your progress saves automatically on your computer.

Download: [pmp_quest.html link]
```
Team Link (GitHub Pages)
Upload `pmp_quest.html` to a public GitHub repo
Enable GitHub Pages in Settings
Share: `https://yourusername.github.io/pmp-quest/`
Team Leaderboard (Optional)
Create a shared Google Sheet for weekly check-ins:
```
Name | Week | Tasks Done | Level | Streak | Total XP
---
Alice | 1 | 28 | 2 | 5 | 450
Bob | 1 | 15 | 1 | 2 | 210
```
---
📖 Tips for Success
Daily Routine
Open the game and expand today's lesson
Read the checklist and complete tasks in order
Do the review loop — reinforce the material
Click study material links to read/watch content
Take the mini-quiz at the end of the day
Check off all tasks — this locks in your daily +10 XP
Week 1–3
Read before practicing — understand concepts before answering questions
Log wrong answers — write them in a notebook to review later
Target 70%+ on quizzes — before moving to the next day
Week 4
Full 180-question mocks — simulate real exam conditions (230 minutes, timed)
Review diagnostics — which domains are you weak in?
Focus > breadth — the last 2 days, deep-dive your weakest area only
Sleep 8+ hours — memory consolidates during sleep
Exam Day
Flag uncertain questions — never spend >2 minutes on one
Read question stems from the end first — identify what's being asked
Your first instinct is usually right — only change answers with a clear reason
Trust the prep — you've got this
---
❓ FAQ
Q: Will this guarantee I pass the exam?
A: No guarantee, but the plan is comprehensive and exam-aligned to PMBOK 7. Success depends on consistent effort, quality study, and real understanding (not memorization).
Q: Do I really need to buy PMBOK 7 separately?
A: No — the full PMBOK 7 Guide is included as a PDF in this repo. Click the "PMBOK 7 Guide" button in the game to read it directly.
Q: The "PMBOK 7 Guide" button says the file isn't found. What do I do?
A: Make sure `PMBOK7.pdf` is in the same folder as `pmp_quest.html`. If you downloaded them separately, drag them into the same folder. If you're using GitHub Pages, make sure both files are in the same directory of the repo.
Q: Can I take this at my own pace?
A: Yes. The plan assumes 4 weeks, but you can speed up or slow down. Set your deadline accordingly.
Q: What if I skip a day?
A: Your streak resets the next time you're inactive for >24 hours. The game tracks this automatically.
Q: Do I need an internet connection?
A: No. After opening the file once, it works completely offline. Study anywhere.
Q: Where does my data go?
A: Nowhere. It stays on your computer in your browser's localStorage. No tracking, no cloud sync.
Q: Can I share my progress with teammates?
A: Your progress is local to your browser. You can screenshot stats or manually log them in a shared sheet. No automatic sync.
Q: What if I clear my browser cache?
A: All progress is erased. Back up your progress data (see "Backing Up" section above) if you're worried.
Q: Is there a mobile app?
A: Not yet, but the web version is fully responsive and works great on mobile browsers.
Q: Can I contribute or suggest features?
A: Feedback is always welcome! Open an issue on the repo or fork and submit a PR.
---
📝 License
This project is provided as-is for educational purposes. PMP and PMBOK are registered trademarks of the Project Management Institute. This is an independent study tool, not affiliated with PMI.
---
🎓 About This Tool
Created for: Intermediate project managers preparing for PMP certification
Exam Format: PMBOK 7th Edition (current through July 8, 2026)
Study Duration: 4 weeks, 1–2 hours/day
Total Tasks: 90 daily checklist items across 28 lessons
Total XP Available: ~3,000+ XP (tasks + streak bonuses + quiz bonuses)
---
🙌 Get Started Now
Download `pmp_quest.html`
Open in your browser
Set your exam date (click the deadline badge)
Start Day 1 — read the topics, complete the checklist
Build your streak — 7 days = +100 XP bonus
Level up → unlock achievements → pass the exam
Good luck, PM! You got this. 🚀
---
📧 Questions or Issues?
Found a bug? Open an issue on GitHub
Want to suggest a feature? Submit a pull request
Want to share your success? Drop a star ⭐
---
Version: 1.0 | Last Updated: April 2026 | Status: Complete & Production-Ready
