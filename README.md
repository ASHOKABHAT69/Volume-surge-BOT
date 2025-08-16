# 📩 Telegram Message Sender

████████╗███████╗██╗ █████╗ ██████╗ ██████╗
╚══██╔══╝██╔════╝██║ ██╔══██╗██╔═══██╗██╔══██╗
██║ █████╗ ██║ ███████║██║ ██║██████╔╝
██║ ██╔══╝ ██║ ██╔══██║██║ ██║██╔══██╗
██║ ███████╗███████╗██║ ██║╚██████╔╝██║ ██║
╚═╝ ╚══════╝╚══════╝╚═╝ ╚═╝ ╚═════╝ ╚═╝ ╚═╝



A Python script to send messages to a Telegram chat using the **Telegram Bot API**.  
Perfect for quick alerts, notifications, or personal reminders.

> **⚠️ Licensing Notice:**  
> This project is **NOT open-source**. All rights reserved.  
> Personal use is free, but **commercial use requires a paid license**.  
> Contact: **ashokabhatfsd@gmail.com** 

---

## ✨ Features

- ✅ Send a **custom message** to any Telegram chat or group
- ⏱ Shows the **exact send time**
- 📡 Displays **HTTP status** and API response
- ⚡ Calculates **round-trip latency**

---

## 📦 Requirements

- Python **3.x**
- [`requests`](https://pypi.org/project/requests/) library

Install dependencies:
bash
pip install requests
⚙️ Setup
1. Create a Telegram Bot
Open Telegram and search for BotFather

Run /newbot → choose a name → get your BOT_TOKEN

2. Get Your Chat ID
Send any message to your bot

Open in browser:

https://api.telegram.org/bot<YOUR_BOT_TOKEN>/getUpdates
Look for "chat":{"id": ...} → that’s your CHAT_ID

3. Edit the Script
BOT_TOKEN = "YOUR_BOT_TOKEN"
CHAT_ID = "YOUR_CHAT_ID"
MESSAGE = "Your message here"

▶️ Usage
Run:
python main.py
Example Output:

Message Sent At: 14:35:21.123456
STATUS :  200
RESPONSE :  {'ok': True, 'result': {...}}
HTTP total round trip time :  0.234 seconds
Sending a Message	Telegram Result

NOTE!! 
If you want the full volume surge project ping in  mail, i cannot upload it here since it's too CONFIDENTIAL.

📜 License
This project is licensed under a Custom Commercial License – see the LICENSE file for details.
No part of this software may be copied, modified, or used commercially without prior permission.
