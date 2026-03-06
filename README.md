# Telegram Beep Bot 🔊

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Telegram](https://img.shields.io/badge/Telegram-Bot-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A Telegram bot that converts text into **binary beep audio** and sends it back as a sound file.  
A fun Python project demonstrating **text encoding, signal generation, and Telegram bot automation**.

---

## ✨ Features

- 🔤 Converts text into **binary**
- 🔊 Generates **beep audio sequence**
- 🤖 Telegram bot interface
- 🐍 Written in **Python**
- ⚡ Lightweight and easy to run

---

## 📦 Requirements

- Python 3.x
- pyTelegramBotAPI
- numpy

Install dependencies:

```bash
pip install pyTelegramBotAPI numpy
```

---

## 🚀 Setup

### 1. Create a Telegram Bot

Open Telegram and talk to **@BotFather**.

Use the command:

```
/newbot
```

Follow the steps and copy the **Bot Token**.

---

## 2. Clone the Repository

```bash
git clone https://github.com/atrx07/Telegram-beep-bot.git
cd Telegram-beep-bot
```

---

## 3. Configure the Script

Open `beep_bot.py` and replace:

```
[Bot token]
```

with your actual Telegram bot token.

---

## 4. Run the Bot

```bash
python beep_bot.py
```

Your bot will now start and respond to messages with **binary beep audio**.

---

## 📂 Example

User sends:

```
Hello
```

Bot responds with:

```
Binary beep audio 🔊
```

---

## 🧠 How It Works

1. User sends text to the bot
2. Text is converted to **binary representation**
3. Binary digits are mapped to **audio tones**
4. Audio waveform is generated
5. The bot sends the resulting **.wav audio file**

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## ⭐ Support

If you like this project, consider giving the repo a **star ⭐** on GitHub.
