# 🚀 Nexora – Lead Capture + Telegram Notifier
This automation instantly captures leads from a Tally form, saves them in Google Sheets, and sends a real-time alert to Telegram — built using **n8n**, **Google Sheets**, and **Telegram Bot API**.
---
## 🔧 How It Works
1. 🧲 Catch Webhook from Tally form submission  
2. 📝 Format & clean lead data  
3. 📊 Append to your Google Sheet  
4. 📩 Send alert to your Telegram via bot
---
## 🛠 Requirements
- n8n account (self-hosted or cloud)
- Google Sheet (your own sheet ID)
- Telegram Bot (via [@BotFather](https://t.me/BotFather))
- Tally form (or any form that supports webhook)
---
## ⚙️ Setup Instructions
1. Import the `Nexora - Lead Capture + Telegram Notifier.json` into your n8n
2. Replace the placeholders:
   - `YOUR_SPREADSHEET_ID` with the ID from your Google Sheet URL  Example: If your URL is https://docs.google.com/spreadsheets/d/1ABCD123456789XYZ/edit#gid=0,
      → Your YOUR_SPREADSHEET_ID = 1ABCD123456789XYZ  
   - `YOUR_CHAT_ID` with your Telegram user/group ID
   - `YOUR_BOT_TOKEN` from @BotFather (Telegram bot)
   - `YOUR_SHEET_GID` is usually just gid=0 (default first sheet). You can keep it as gid=0 unless you're using a renamed or different sheet tab.
3. Activate the workflow — done!
---
## 🔁 Workflow Diagram
![N8N Workflow](https://github.com/NexoraFlow/nexora-lead-telegram-bot/raw/main/workflow-diagram.JPG)
## 📂 Files Included
| File Name | Purpose |
|-----------|---------|
| `Nexora - Lead Capture + Telegram Notifier.json` | Main workflow |
| `README.md` | Setup instructions and overview |
---
🎁 [Download the Telegram Lead Bot](https://nexoraflow.gumroad.com/l/telegram-lead-bot)
## 🔐 License
Use freely. Attribution to **Nexora** is appreciated.
