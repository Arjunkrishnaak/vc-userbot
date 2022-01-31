# Telegram Voice Chat User Bot
A Telegram Userbot to play Audio and Video songs / files in Telegram Voice Chats.

It's made with [PyTgCalls](https://github.com/pytgcalls/pytgcalls) and [Pyrogram](https://github.com/pyrogram/pyrogram)

# Environment Variables
- `API_ID`
- `API_HASH`
- `SESSION` - A Pyrogram String Session. Get one from [Here](https://replit.com/@ZauteKm/GenerateStringSession)
- `HNDLR` - Your Userbot Handler (Default is !)
- `GROUP_MODE` - if Value is set to `True`, Anyone can Play. Set it to `False` to restrict play access to Sudo Users/Contacts only.

## Deployment

### Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Railway
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Flushaimusic%2Fvc-userbot%2Ftree%2Fmaster&envs=API_HASH%2CAPI_ID%2CGROUP_MODE%2CHNDLR%2CSESSION&GROUP_MODEDesc=Required+Anyone+can+play%2C+if+set+to+True.+Set+it+to+False+to+restrict+play+access+to+Sudo+Users%2FContacts+only&HNDLRDesc=Handler+%7C+Default+%28%21%29&referralCode=Lvx2)

### Local Deploy
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

3) Cloning the Repo
```bash
git clone https://github.com/lushaimusic/vc-userbot
cd vc-userbot
```

4) Rename `example.env` to `.env` and Fill in the Environment Variables

5) Installing Requirements
```bash
pip3 install -U -r requirements.txt
```

6) Run the Bot
```bash
python3 main.py
```

## Commands and Usage
1) Start the Userbot, check if the Userbot is running by `!ping`.
2) Commands of this userbot are accessible to and can be used by the Account itself and it's Contacts.
3) Check `!help` for commands.

## Credits ✨
- [Dan](https://github.com/delivrance) for [Pyrogram](https://github.com/pyrogram/pyrogram)
- [Laky](https://github.com/Laky-64) for [PyTgCalls](https://github.com/pytgcalls/pytgcalls)
