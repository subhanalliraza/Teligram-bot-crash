# Telegram WebSocket Crash Bot

یہ ایک Telegram bot ہے جو مخصوص گیم کے WebSocket سے connect ہوتا ہے،  
ہر نئے راؤنڈ کے شروع ہونے سے 10 سیکنڈ پہلے alert دیتا ہے،  
اور خودکار طور پر 10 منٹ بعد بند ہو جاتا ہے۔

## 🚀 Features
- WebSocket سے live signals
- Telegram alerts
- Password-protected start
- 10 minutes auto-stop
- GitHub Actions پر چلتا ہے

---

## 📦 Setup Instructions

### 1. Repository Clone یا Create کریں
یہ repo اپنی GitHub پر رکھیں۔

### 2. Secrets Add کریں
GitHub → Settings → Secrets and variables → Actions → **New repository secret**  
یہ secrets add کریں:

| Name              | Example Value |
|-------------------|--------------|
| `TELEGRAM_TOKEN`  | 123456:ABC-DEF... |
| `TELEGRAM_CHAT`   | 7525979955 |
| `WS_URL`          | wss://example.com/your_game_ws_link |
| `BOT_PASSWORD`    | Shedo786 |

---

### 3. Run Workflow
- Repo میں **Actions** tab کھولیں
- **Run Bot for 10 Minutes (Password Protected)** منتخب کریں
- **Run workflow** دبائیں
- پاسورڈ ڈالیں → Bot چل جائے گا

---

## 📜 License
یہ code educational purposes کے لیے ہے۔ Use at your own risk.
