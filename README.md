# n8n-workflows
This repository is where I build and experiment with automation workflows using n8n.
I use it as a hands-on space to learn how different tools can talk to each other and how small systems can be designed to solve simple, real problems.
---
## What this repo is about
Instead of just reading about automation, I prefer building things.
Here I connect tools like:
- Google Calendar  
- Google Sheets  
- Gmail  
- Telegram  
- External APIs  
Each project focuses on one clear use case and is structured in its own folder with documentation and the exported workflow file.
---
## Projects
###  Google Calendar → Telegram Automation
This workflow sends my daily Google Calendar meetings to Telegram automatically.
What it does:
- Runs every day at a scheduled time  
- Fetches that day's calendar events  
- Formats the information using JavaScript  
- Sends a clean message to Telegram  
The goal of this project was to practice:
- API integration  
- Data formatting  
- Scheduled automation  
- Message delivery through a bot  
Folder: `calendar-telegram-automation`
---
###  Sales Summary Automation
This workflow monitors a Google Sheet and sends an email report when data changes.
What it does:
- Detects updates in Google Sheets  
- Applies simple IF logic  
- Processes and counts order data  
- Sends an automated email via Gmail  
The focus here was on:
- Trigger-based workflows  
- Conditional logic  
- Data processing  
- Email automation  
Folder: `sales-summary-automation`
---
## Why I’m building this
I’m using these projects to improve my system thinking and automation skills step by step.
Each workflow is small, but built with intention:
clear structure, readable logic, and practical use cases.

This repository will grow as I continue building more integrations and experimenting with new ideas.
