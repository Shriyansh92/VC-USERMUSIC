# TG-MusicPlayer
A Telegram Userbot to play Audio and Video songs / files in Telegram Voice Chats.

It's made with [PyTgCalls](https://github.com/pytgcalls/pytgcalls) and [Pyrogram](https://github.com/pyrogram/pyrogram)


## Requirements
- Python 3.8+
- FFMPEG
- Nodejs v16+


## Deployment

### Heroku
## 🚀 <a name="deploy"></a>Deploy


[![Deploy on Heroku](="https://heroku.com/deploy"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>https://github.com/Shriyansh92/MUSIC-VC_PLAYER)


[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Shriyansh92/VC-USERMUSIC)


1) Installing NodeJS
```bash
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs
```

2) Installing Dependencies
```bash
sudo apt-get install git ffmpeg -y
sudo apt-get install youtube-dl -y
```


3) Installing Requirements
```bash
pip3 install -U -r requirements.txt
```

4) Run the Bot
```bash
python3 main.py
```


## Environment Variables
- `API_ID`
- `API_HASH`
- `SESSION` - A Pyrogram String Session.
- `HNDLR` - Your Userbot Handler (Default is /)
- `GROUP_MODE` - if Value is set to `True`, Anyone can Play. Set it to `False` to restrict play access to Sudo Users/Contacts only.


## Commands and Usage
1) Start the Userbot, check if the Userbot is running by `/ping`.
2) Commands of this userbot are accessible to and can be used by the Account itself and it's Contacts.
3) Check `/help` for commands.

