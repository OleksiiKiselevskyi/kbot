# kbot
devops application from scratch

Simple telegram bot, vesrion 1.0.2

Link to bot instance: [kbot](https://t.me/OleksiiKiselevskyi_bot)

At this point it can only respond to "/start hello" command

To launch your own instance of kbot, you will need to:

1. Download latest build: [v1.0.2](https://github.com/OleksiiKiselevskyi/kbot/releases/tag/v1.0.2) and unpack it
2. Get token for your telegram bot instance from [BotFather](https://t.me/BotFather)
3. Assign the token value to TELE_TOKEN variable:
    * simply run `TELE_TOKEN = <insert_your_token_value>`
    * or run `read -s TELE_TOKEN` and then paste your token value if you don't want it to appear in terminal logs
4. Export TELE_TOKEN value: `export TELE_TOKEN`
5. Run kbot: `./kbot start`

Available commands:
* `./kbot version` (TELE_TOKEN initialization isn't required)
* `./kbot start`