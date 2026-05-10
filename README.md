# Oppen

A basic Python Telegram bot that responds to commands and echoes messages.

## Features

- `/start` - Sends a welcome message
- `/help` - Shows available commands
- Echoes back any text message sent to the bot

## Setup

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Set your Telegram bot token as an environment variable:

```bash
export TELEGRAM_BOT_TOKEN="your-bot-token-here"
```

You can get a bot token by talking to [@BotFather](https://t.me/BotFather) on Telegram.

3. Run the bot:

```bash
python bot.py
```

## Configuration

| Environment Variable | Description | Required |
|---------------------|-------------|----------|
| `TELEGRAM_BOT_TOKEN` | Your Telegram bot API token | Yes |
