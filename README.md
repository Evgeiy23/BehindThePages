# BehindThePages

# Requirements for the Telegram Bot Project

1. Python 3.8 or higher
2. aiogram library for Telegram bot interactions
3. groq library for AI interactions
4. asyncio for asynchronous operations
5. logging for error handling and debugging
6. re for text processing

# Installation

To install the required dependencies, run:

```bash
pip install aiogram groq
```

# Configuration

1. Create a `config.py` file with the following variables:
   - `TELEGRAM_BOT_TOKEN`: Your Telegram bot token
   - `GROQ_API_KEY`: Your Groq API key

2. Ensure the bot token and API key are valid and have the necessary permissions.

# Running the Bot

To start the bot, run:

```bash
python main.py
```

# Dependencies

- aiogram: For Telegram bot interactions
- groq: For AI interactions
- asyncio: For asynchronous operations
- logging: For error handling and debugging
- re: For text processing

# Notes

- Ensure all dependencies are installed before running the bot.
- The bot requires a stable internet connection to interact with the Telegram API and Groq API.
- The bot uses asynchronous operations, so ensure your environment supports asyncio.
