# 📱LepakSGbot
A Telegram bot that recommends chill spots around Singapore based on pre-written town and category preferences.

## 🛠️ Technology
- `Python`
- `BotFather`
- `JSON`

## 🚀 Features
- **Location-based recommendations** - suggests chill-out spots around Singapore according to the user’s selected town (and category, when provided)
- **Flexible data-driven configuration** - towns, categories, and reply templates are defined in JSON files for easy modification
- **Works on Telegram** - users interact with the bot through commands and messages to get suggestions

## 🧠 The Process
My friends and I would constantly be faced with a dilemma on where we should hang out, so I  built LepakSGbot to help us and other friend groups discover nice chill spots around Singapore based on what kind of mood or area they’re in. Instead of hard-coding every possible reply, I structured the bot to load its data (towns, categories, reply templates) from JSON files. This makes it super easy to extend the list of towns or categories without touching the code logic.

When a user sends a message, the bot processes the input [via functions like `get_response()` or `handle_response()` ], matches the town (and optionally a category), then sends back a formatted recommendation. The logic lives in `main_telegram.py`, which handles commands, message listening, and inline button callbacks. Using a data-driven approach with JSON plus a bot registered via BotFather gave me simple, maintainable code and flexibility to expand later.

## 📦 Running the Project
If you wish to use the repository, use your own token. I am not providing LepakSG’s token.

1. Clone or download the repository
2. Make sure you have Python installed
3. Register your bot with BotFather on Telegram.
4. Add the token to your configuration file or environment variable
5. Run the bot: python main_telegram.py
6. Open Telegram, find your bot, and send a command or message to receive place recommendations

## 🖼️ Preview
![Image](https://github.com/user-attachments/assets/e2b483ae-8654-4740-a459-d73aa5d6cc32)
