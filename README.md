# DHA Nursing Practice Exam

A web-based practice exam application for **Dubai Health Authority (DHA) Nursing Licensure Examination** preparation. Built as a single HTML file that runs entirely in the browser — no installation, no server, no internet required.

---

## Features

- **3,998 MCQ questions** across 5 nursing subjects
- **150 randomly selected questions** per exam based on DHA subject weightage
- **165-minute countdown timer** with pause/resume
- **Warning alert at 160 minutes** — exam auto-submits at 165 minutes
- **Full question navigation** — jump to any question, go back and change answers
- **Flag questions** for review
- **Detailed results** — total score, pass/fail indicator, subject-wise performance breakdown
- **Answer review** — see correct answers with filter (all / wrong / correct / unanswered)
- **Unlimited retakes** — each exam draws a fresh random set of questions

## Subject Weightage

| Subject | Weight | Questions per Exam |
|---|---|---|
| Fundamentals of Nursing | 25% | ~38 |
| Unit Management / Leadership | 22% | ~33 |
| Adult Nursing | 20% | ~30 |
| Pediatric Nursing | 18% | ~27 |
| Maternal Health Nursing | 15% | ~23 |

## Question Bank

| Subject | Available Questions |
|---|---|
| Adult Nursing | 1,988 |
| Fundamentals of Nursing | 754 |
| Pediatric | 668 |
| Maternal Health Nursing | 335 |
| Unit Management / Leadership | 253 |
| **Total** | **3,998** |

## How to Use

### Run Locally (Recommended)

1. Download `DHA_Nursing_Practice_Exam_Standalone.html`
2. Double-click to open in any browser (Chrome, Edge, Firefox, Safari)
3. Click **Start Exam**

That's it. Everything is self-contained in one file.

### Run as a Website (GitHub Pages)

1. Fork or clone this repository
2. Go to **Settings → Pages → Branch: main → Save**
3. Access your exam at `https://yourusername.github.io/dha-nursing-practice/`

### Other Platforms

The standalone HTML file works on any platform that can open an HTML file — **CodePen**, **Replit**, **JSFiddle**, or any web browser on Windows, Mac, Linux, Android, or iOS.

## Files

| File | Description |
|---|---|
| `index.html` | Standalone exam app (all questions embedded, works offline) |
| `DHA_Nursing_Practice_Exam.html` | Exam app (loads questions from external file) |
| `qdata.js` | Question bank data file (used with the two-file version) |
| `Question_Bank_Database_Updated_06.xlsx` | Source Excel database |

## Screenshots

### Home Page
- Exam instructions and subject weightage
- Start button to begin the exam

### Exam Interface
- Question display with multiple choice options
- Timer, question navigator, pause/resume, and flag for review
- Progress tracking

### Results Page
- Score percentage with pass/fail indicator
- Subject-wise performance breakdown with visual bars
- Full answer review with correct/incorrect highlighting

## Tech Stack

- **HTML5 / CSS3 / Vanilla JavaScript** — zero dependencies
- **No frameworks, no build tools, no server required**
- Runs entirely client-side in the browser

## License

This project is for educational and personal exam preparation purposes only.

---

**Created by: Blenson Paul**
