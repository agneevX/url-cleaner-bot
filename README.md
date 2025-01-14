# URL Cleaner Bot

![url_image](https://user-images.githubusercontent.com/19761269/199670096-c4b74d2d-41fb-4fea-9894-a4d865896ed9.jpg)

A (_minimalist_) Telegram bot to provide clean URLs and removes any tracking info in the URL.

Self-hosted version here: https://t.me/clean_urls_bot

This bot utilises two libraries (credit to the creators)
    
    1. Telethon
    2. Unalix

#### Usage

1. Send a link and the bot will reply with a clean URL
2. Add the bot in a group and the bot will reply with clean URLs there

##### Self-host

```
git clone https://github.com/agneevX/url-cleaner-bot
cd url-cleaner-bot
```

- Follow this [guide](https://docs.telethon.dev/en/stable/basic/signing-in.html "setup guide") to get `api_id`, `api_hash` and `bot_token`
- Replace those values in `CONFIG.py`

```
docker build . -t url-cleaner-bot
docker run -d url-cleaner-bot
```
