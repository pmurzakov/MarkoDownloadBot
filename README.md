# Marko Download Bot

This is a Telegram bot that receives URL to a video for popular sites like Instagram, TikTok, YouTube, etc. and responds with a downloaded video. It is convenient for sharing content with your friends and family.

![GIF](MarkoDownloadBot.gif)

## Installation

1. Create a new bot using Bot Father (https://t.me/BotFather). Remember your token
2. Acquire API ID and Hash from https://my.telegram.org/apps. Remember them
3. Clone this repository: `git clone https://github.com/marko/MarkoDownloadBot.git`
4. Navigate to the project directory: `cd MarkoDownloadBot`
5. Create file `.env` with this content:
```
TELEGRAM_API_ID=<api_id>
TELEGRAM_API_HASH=<api_hash>
TELEGRAM_BOT_API_TOKEN=<bot_token>
ADMIN_USERNAME=<your_telegram_username>
```
6. Run the bot using docker compose: `docker compose up -d`
7. Write `/start` to your new Telegram bot

## Usage

There is only one command: `/stats`. It gives you some basic statistics.
Otherwise just send a URL to a bot and it will give you a video.

## Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
