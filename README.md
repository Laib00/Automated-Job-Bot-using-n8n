# 🚀 AI Job Finder (n8n Automation)

This project is an automated job discovery system built using n8n to simplify the job hunting process.

Instead of manually browsing multiple job platforms, this workflow collects, filters, and ranks relevant jobs daily and delivers them directly via Telegram.

---

## 🧠 Features

- Fetches job listings from APIs (Adzuna, Remotive)
- Focuses on Singapore-based and remote roles
- Filters relevant job opportunities
- Ranks jobs using keyword-based scoring (AI/Data roles)
- Sends top matches automatically to Telegram

---

## ⚙️ Tech Stack

- n8n (workflow automation)
- HTTP APIs (Adzuna, Remotive)
- JavaScript (data transformation & ranking)
- Telegram Bot API

---

## 🔄 Workflow Overview

Cron → API Calls → Merge → Normalize → Filter → Rank → Format → Telegram

---

## 📦 Project Structure

- `n8n-ai-job-finder.json` → Exported workflow
- `workflow.png` → Workflow screenshot

---

## 🚀 How to Use

1. Import the workflow JSON into n8n
2. Add your Adzuna API credentials
3. Configure your Telegram bot and chat ID
4. Execute or schedule the workflow

---

## 💡 Motivation

While job hunting, I noticed how repetitive and time-consuming it was to check multiple platforms daily.

This project automates the process and highlights the most relevant opportunities, saving time and improving focus.

---

## 🔮 Future Improvements

- AI-based ranking using OpenAI
- Remove duplicate job listings
- Store jobs in a database
- Build a dashboard for tracking applications

---

## 🤝 Connect

If you're exploring automation, n8n, or similar projects, feel free to connect!
