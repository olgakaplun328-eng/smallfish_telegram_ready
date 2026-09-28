# Smallfish on Railway

This package starts the original Smallfish application with Telegram enabled:

    python src/app.py --telegram

Required Railway Variables:
- MEXC_API_KEY
- MEXC_API_SECRET
- TELEGRAM_BOT_TOKEN
- TELEGRAM_CHAT_ID

The MEXC credentials are required by the original Smallfish application even though
Telegram is only the notification/control layer. The trading logic was not replaced
with KELTRADER and no 15-minute KELTRADER scanner is included.

The repository's `config/default.yaml` is used as the application configuration.
