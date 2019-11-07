# BuptPowerOffDate_bot
Telegram Link: [http://t.me/BuptPowerOffDate_bot](http://t.me/BuptPowerOffDate_bot)

forked from https://github.com/imxieyi/sticker_time_bot

## Introduction
This is a [Telegram](https://telegram.org/) bot sending a sticker telling power off or not. You can start or stop any time using commands.

## Commands
**Start sending stickers:** `/start`

**Stop sending stickers:** `/stop`

**Set timezone:** `/timezone Asia/Shanghai`

*List of timezones in tz database: [https://en.wikipedia.org/wiki/List_of_tz_database_time_zones](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)*

**Enable/Disable auto deleting messages:** `/autodelete [on|off]`

**Set sleep time:** `/sleeptime [0-23]`

**Set wake time:** `/waketime [0-23]`

## Environment
- Node.js 8.0+

## Installation
```sh
npm install
```

## Configuration
Create a file config.json:
```json
{
    "tg_bot_token": "Your Telegram bot token here",
    "log_file": "Log file"
}
```

## Start
```sh
npm start
```
