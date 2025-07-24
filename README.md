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
   - `YOUR_SPREADSHEET_ID` with your Sheet ID
   - `YOUR_CHAT_ID` with your Telegram user/group ID
   - `YOUR_BOT_TOKEN` with your bot token from @BotFather
3. Activate the workflow — done!
---
## 📂 Files Included
| File Name | Purpose |
|-----------|---------|
| `Nexora - Lead Capture + Telegram Notifier.json` | Main workflow |
| `README.md` | Setup instructions and overview |
---
## 🔐 License
Use freely. Attribution to **Nexora** is appreciated.
