# 🛠️ Blubz Tool - Discord Multi Tool Bot

A clean, safe, and feature-rich Discord bot written in Python using `discord.py`, with a stylish command-line banner and essential utilities.

---

## ✨ Features

- 🏓 `!ping` – Shows bot latency
- ⏱️ `!uptime` – See how long the bot has been online
- 🏠 `!serverinfo` – Get details about the server
- 👤 `!userinfo` – Get info about yourself or any mentioned user
- 🧹 `!clear [amount]` – Clear messages quickly (needs `Manage Messages`)
- 🪙 `!coinflip` – Flip a coin (Heads or Tails)
- 🔢 `!randomnum [min] [max]` – Generate a random number between two values

---

## ⚙️ Setup Guide

### 1. Clone the Repo

```bash
git clone https://github.com/ProjectVelocity1/blubz-s-bot-tool
cd discord-multi-tool
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Add Your Bot Token
Edit the bot.py file and replace:
```python
bot.run("YOUR_BOT_TOKEN_HERE")
```
### 🧠 Requirements
Python 3.10+

discord.py

colorama

pyfiglet

Install all with:
```bash
pip install -r requirements.txt
```
### 🔗 Invite the Bot
To invite the bot to your server:

Go to the Discord Developer Portal

Select your app → OAuth2 > URL Generator

Choose:

```
bot
applications.commands
```
Permissions needed:
```
Send Messages
Read Message History
Embed Links
Manage Messages (optional for !clear)
```
Copy and paste the generated link in your browser and invite your bot!
