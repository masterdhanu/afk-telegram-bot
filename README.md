# caps-tv-afk-telegram-bot
A simple AFK Python Telegram bot for one chat running
 on python3 with an sqlalchemy database inspired by [Pranaov](https://t.me/pranaovs) and made by [Roj](https://t.me/rojserbest).

## Configuring variables

- `DATABASE_URL`: your database url.
- `CHAT_ID`: your Telegram group chat id.
- `TOKEN`: the bot API key that [Botfather](https://t.me/botfather) generated.


## Deploying to Heroku

1. Fork this repository.
2. Create your app.
3. Add "Heroku Postgres" add-on to your app.
4. Go to Heroku dashboard > your app name > settings > reveal config vars and add the config vars (`CHAT_ID`, `TOKEN`).
5. Deploy your app and you are good to go. 
`Fork and Click on Deploy in your fork`
<p><a href="https://heroku.com/deploy"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-black?style=for-the-badge&logo=heroku" width="250""/></a></p>
