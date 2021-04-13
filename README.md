# KryPtoN Music Bot



Music on Voice Calls Telegram

# Support
- Python 3.7 or above
- All distro linux (Ubuntu 18.04 not work)
- Windows
- Mac

# Requirements
- Telegram API_ID and API_HASH [Get here](https://my.telegram.org/apps)
- Python 3.7 or higher
- Needs user account not bot from bot father
- Install ffmpeg

# Usage
Install package required
```
$ git clone https://github.com/Kry9toN/KryPtoN-Music-Bot
$ cd KryPtoN-Music-Bot
$ pip install -r requirements.txt
```
Setup config
configs.py and edit

Execute!
```
$ python3 -m krypton
```

# Heroku 

[![Heroku Badge](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Tievodj/player/tree/master)

### Generate String session [IMPORTANT]
Download this file [generate_string_session.py](https://raw.githubusercontent.com/Kry9toN/KryPtoN-Music-Bot/master/generate_string_session.py)

```
$ pip3 install pyrogram TgCrypto
$ python3 generate_string_session.py
```
You will get a session string, copy it, Then use heroku commands to push to heroku

## Commands
Command | Description
:--- | :---
/start | To Start The bot.
/help | To Show This Message.
/ping | To Show Latency Bot.
/skip | To Skip The Current Playing Music.
/play | youtube/saavn/deezer song_name
/stop | To Stop Playing Music.
/join | To Join A Voice Chat.
/leave | To Leave A Voice Chat.
/mute | To Mute A Bot.
/unmute | To Unmute A Bot.
/volume | <1-200>
/kill | To Kill A Sevice Bot.
/donation | To Give Me A Coffe.


