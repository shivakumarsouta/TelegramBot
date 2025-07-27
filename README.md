# Horoscope Telegram Bot

A simple, user-friendly Telegram bot that provides daily, tomorrow's, or yesterday's horoscopes for all zodiac signs. Powered by Python and the Telebot (pyTelegramBotAPI) library, using data from the Horoscope API.

## ✨ Features

- Get horoscopes for:
  - Today
  - Tomorrow
  - Yesterday
  - Specific date (`YYYY-MM-DD` format)
- Supports all 12 zodiac signs
- Simple conversational flow
- Automatic error handling with restart

---

# 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/shivakumarsouta/TelegramBot.git
cd TelegramBot
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Set Up Environment Variables

Create a `.env` file in the root directory:

```
BOT_TOKEN=your-telegram-bot-token
```

Make sure `.env` is included in `.gitignore` to keep your token secure.

### 4️⃣ Run the Bot

```bash
python bot.py
```

---

# 🛠️ Project Structure

```
├── bot.py                # Main bot script
├── utils.py              # Utility function for fetching horoscopes
├── .env                  # Environment variables (not pushed to repo)
├── .gitignore            # Files to ignore in git
├── requirements.txt      # Python dependencies
└── README.md             # Project README
```
---

# 📋 Commands

- `/start` or `/hello` or `/hi` – Greets the user.
- `/horoscope` – Starts horoscope flow:
  1. User chooses zodiac sign.
  2. User chooses date (Today, Tomorrow, Yesterday, or YYYY-MM-DD).

---
# 📎 Dependencies

- Python 3.8+
- `pyTelegramBotAPI`
- `requests`

---

# ✅ Example Usage

- User sends `/horoscope`.
- Bot asks for zodiac sign.
- User replies with `"Leo"`.
- Bot asks for date.
- User replies with `"TODAY"`.
- Bot sends back the horoscope.

---

# ⚠️ Notes

- Make sure your Telegram bot token is valid.
- API endpoint: [Horoscope App API](https://horoscope-app-api.vercel.app/)
- Be aware of rate limits from the API provider.

---

# 📄 License

This project is open-source under the [MIT License](LICENSE).

---

# 🙏 Credits

FreeCodeCamp

---
