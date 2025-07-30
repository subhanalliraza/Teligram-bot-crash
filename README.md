# Telegram WebSocket Crash Bot

This is a WebSocket-powered Telegram bot that sends real-time game alerts.  
It warns **10 seconds before each round starts**, runs for **10 minutes**, and then stops automatically.  
Designed to run on **GitHub Actions** using repository secrets.

---

## 🚀 Setup Instructions

### 1. Create Telegram Bot
- Open Telegram, search for **@BotFather**
- Send `/newbot` and follow the instructions
- Copy the token you receive

### 2. Get Your Chat ID
- Open Telegram, search for **@userinfobot**
- Send `/start`
- Note the `Id` number (your chat ID)

### 3. Get WebSocket URL
- Example:
