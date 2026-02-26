# Google Calendar → Telegram Automation

This workflow automatically sends today's Google Calendar meetings to Telegram.

## Overview

Every day at a scheduled time, this automation:

- Fetches today's events from Google Calendar
- Formats meeting details (time + title)
- Sends a message to Telegram

## Workflow Structure

Schedule Trigger  
→ Google Calendar (Get Events)  
→ Set / Code (Format message)  
→ Telegram (Send Message)

## Features

- Daily automatic execution
- Europe/Berlin timezone support
- Handles multiple meetings
- Clean Telegram message output
- Handles empty days (no meetings)

## Example Output

Meetings (Europe/Berlin)

• 09:00 — Team Sync  
• 13:30 — Client Call  
• 16:00 — Project Review  

## Tech Stack

- n8n
- Google Calendar API
- Telegram Bot API
- JavaScript (Code node)

## Purpose

This project was built to practice workflow automation using n8n and external APIs.

It demonstrates:
- API integration
- Data formatting
- Automation scheduling
- Real-time messaging systems
