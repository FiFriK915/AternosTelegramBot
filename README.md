# THIS BOT IS NOT RELEVANT! ATERNOS HAS MADE DRASTIC CHANGES TO ITS API! THIS SOLUTION NO LONGER WORKS\RELEVANT 

```
# Aternos Telegram Bot on aiogram 3.0.0b8 and python_aternos 3.0.0



# With this bot, you can start, stop and restart the server, view the list of players, the memory used in your telegram bot

## The bot is based on an unofficial library for working with the Atheros API, from the developer python_atheros

> **Warning**
>
> According to the
>
>
> Aternos' [Terms of Service §5.2e](https://aternos.gmbh/en/aternos/terms#:~:text=Automatically%20accessing%20our%20website%20or%20automating%20actions%20on%20our%20website.),
> you must not use any software or APIs for automated access,
> beacuse they don't receive money from advertisting in this case.
>
> I always try to hide automated python-aternos requests
> using browser-specific headers/cookies,
> but you should make backups to restore your world
> if Aternos detects violation of ToS and bans your account
> (view issues [#16](https://github.com/DarkCat09/python-aternos/issues/16)
> and [#46](https://github.com/DarkCat09/python-aternos/issues/46)).

# Everything you need to install for the bot to work

    This project

#

    Python not lower than version 3.10

# Before launching the bot

### You need to rename .env.dist to .env and enter data into it

> ADMINS these are fields for entering telegram IDs of users who will be able to use your bot

> **Warning**
>
> Be careful who you give access to, will be able to manage your servers

> You can get them, for example, from a [BOT IN A TELEGRAM](https://t.me/getmyid_bot)
>
> BOT_TOKEN This is the main token for the bot to work, you need to get it using
> the [OFFICIAL BOT IN TELEGRAM](https://t.me/BotFather)

## You have several ways to log in to Aternos

> LOGIN / PASS 
> 
> OR
> 
> LOGIN / PASSHASH(MD5)

#### Fill in the fields by which you want to log in, leave the rest empty, the bot will figure out what to use

### .env example

```
    ADMINS=1234567,7654321
    TELEGRAM_TOKEN=123456:aasdgsdf
    LOCALE=en or ru
    ATERNOS_LOGIN=
    ATERNOS_PASS=
    ATERNOS_PASS_HASH=
```
```
> Buttons language supported: russian and english

### Now, run start.bat, you should have the console open and the bot will start in [pooling mode](https://core.telegram.org/bots/api#getupdates)
