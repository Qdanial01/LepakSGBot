# LepakSGbot_Tele
LepakSGbot is a Telegram bot that recommends places to chill ("lepak") around Singapore based on pre-written town and category preferences.

## How it works
- 

## Files Features
1. Data (towns, categories, reply templates) are stored in *.json files and loaded in response.py.
2. get_response() or handle_response() processes input, matches town and optional category and then returns a formatted suggestion.
3. Logic is in main_telegram.py and main_discord.py, including command handlers, message listeners, and inline button callbacks.
