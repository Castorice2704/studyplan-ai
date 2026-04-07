# StudyPlan AI 📚

An AI-powered personalized study plan generator built with pure HTML/CSS/JS 
and Google Gemini 2.5 Flash.

## Live Demo
Open `index.html` directly in any browser — no server needed.

## Features
- AI-generated personalized study schedule weighted by subject confidence
- Streaming plan generation with live typing effect
- Weekly calendar view with color-coded subject blocks
- Pomodoro timer with AudioContext completion beep
- Daily check-in with AI plan reshuffle on struggle
- Analytics dashboard with Chart.js charts and activity heatmap
- Gamification — XP system, streaks, and 8 achievement badges
- Mood-based daily adjustment
- PDF export via window.print()
- AI-generated resource kit per subject
- Full localStorage persistence — no backend required

## Tech Stack
- Pure HTML5 / CSS3 / Vanilla JavaScript (single file)
- Google Gemini 2.5 Flash API
- Chart.js (CDN)
- Web Storage API (localStorage)
- Web Audio API

## Setup
1. Clone the repository
2. Open `index.html` in your browser
3. Replace `YOUR_KEY_HERE` in the file with your Gemini API key from aistudio.google.com
4. That's it — no npm install, no build step

## Project Structure
studyplan-ai/
└── index.html       # Entire application in one file
└── README.md

## Built With
- Google Gemini 2.5 Flash for AI plan generation
- Claude for AI-assisted development
- Developed as a Web Development Final Exam Project for Web Development class 23AI2002

## Author
ItsTheDemiGod | B.Tech AI & ML | Batch 2023–2027