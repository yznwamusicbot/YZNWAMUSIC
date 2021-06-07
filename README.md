# YZNWAMUSIC
[![LEGENDMUSIC logo](https://telegra.ph/file/4c96dc821c1d9375c033a.jpg)](https://t.me/Abcdmukakntl)


-It is inspired from su music project and hamkercat's telegram voice bot.
Neither su music project , nor pytgcalls are stable


<p align="center">
<a href="https://app.codacy.com/gh/LEGEND-OS/LEGENDMUSIC?utm_source=github.com&utm_medium=referral&utm_content=LEGEND-OS/LEGENDMUSIC&utm_campaign=Badge_Grade_Settings" alt="Codacy Badge">
<img src="https://api.codacy.com/project/badge/Grade/6141417ceaf84545bab6bd671503df51" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDMUSIC" alt="Libraries.io dependency status for GitHub repo"> <img src="https://img.shields.io/librariesio/github/LEGEND-OS/LEGENDMUSIC" /> </a>
<a href="http://hits.dwyl.com/LEGEND-OS/LEGENDMUSIC" alt="HitCount"> <img src="http://hits.dwyl.com/LEGEND-OS/LEGENDMUSIC.svg" /> </a>
</p>
<p align="center">
<a href="https://github.com/LEGEND-OS/LEGENDMUSIC" alt="GitHub closed issues"> <img src="https://img.shields.io/github/issues-closed-raw/LEGEND-OS/LEGENDMUSIC?style=flat&logo=github&color=success" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDMUSIC" alt="GitHub commit activity"> <img src="https://img.shields.io/github/commit-activity/m/LEGEND-OS/LEGENDMUSIC" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDMUSIC/graphs/contributors" alt="GitHub contributors"> <img src="https://img.shields.io/github/contributors/LEGEND-OS/LEGENDMUSIC?style=flat&logo=github" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDMUSIC/network/members" alt="GitHub forks"> <img src="https://img.shields.io/github/forks/LEGEND-OS/LEGENDMUSIC?label=Forks&logo=github" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDMUSIC" alt="GitHub closed pull requests"> <img src="https://img.shields.io/github/issues-pr-closed-raw/LEGEND-OS/LEGENDMUSIC?color=success" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDMUSIC" alt="GitHub issues"> <img src="https://img.shields.io/github/issues-raw/LEGEND-OS/LEGENDMUSIC?style=flat&logo=github&color=yellow" /> </a>
</p>
<p align="center">
<a href="https://github.com/LEGEND-OS/LEGENDMUSIC" alt="GitHub release (latest by date including pre-releases)"> <img src="https://img.shields.io/github/v/release/LEGEND-OS/LEGENDMUSIC?include_prereleases?style=flat&logo=github" /> </a>
<a href="https://www.python.org/" alt="made-with-python"> <img src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg?style=flat&logo=python&color=blue" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDMUSIC" alt="Docker!"> <img src="https://aleen42.github.io/badges/src/docker.svg" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDMUSIC" alt="GitHub repo size"> <img src="https://img.shields.io/github/repo-size/LEGEND-OS/LEGENDMUSIC" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDMUSIC/blob/master/LICENSE" alt="GPLv3 license"> <img src="https://img.shields.io/badge/License-GPLv3-blue.svg" /> </a>
</p>
<p align="center">
<a href="https://t.me/Legend_Mr_Hacker" alt="Telegram!"> <img src="https://aleen42.github.io/badges/src/telegram.svg" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDMUSIC/graphs/commit-activity" alt="Maintenance"> <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" /> </a>
<a href="https://makeapullrequest.com" alt="PRs Welcome"> <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" /> </a>
</p>


## Requirements

- FFmpeg
- NodeJS [nodesource.com](https://nodesource.com/)
- Python 3.7+
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls)

## Deployment

### Config

Copy `example.env` to `.env` and fill it with your credentials.

### Without Docker

1. Install Python requirements:
   ```bash
   pip install -r requirements.txt
   ```
2. Run:
   ```bash
   python main.py
   ```

### Using Docker

1. Build:
   ```bash
   docker build -t musicplayer .
   ```
2. Run:
   ```bash
   docker run --env-file .env musicplayer
   ```

## The easiest way to deploy this Bot
### HEROKU
<a href="https://heroku.com/deploy?template=https://github.com/LEGEND-OS/LEGENDMUSIC"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-red?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

### StringSession

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@KrishnaJaiswal1/LEGENDMUSIC#main.py) 


### Mandatory Vars.

- Some Of The Mandatory Vars Are :-
   - `API_ID` :  Give API_ID of your Alternate Telegram Account. also get from here [@APIInfoBot](https://t.me/APIinfoBot)
   - `API_HASH` :  Give API_HASH of your Alternate Telegram Account. also get from here [@APIInfoBot](https://t.me/APIinfoBot)
   - `STRING_NAME` :  Make a string session from [here](https://replit.com/@QueenArzoo/VCPlayBot)
   - `BOT_TOKEN` :  Make a Bot from [@Botfather](https://t.me/botfather) and fill it's bot token.
   - `SUDO_USERS` :  Fill Userid of yhe users whom you want to be able to control the bot. You can add multiple id by giving a space in b/w each id.


### Commands 🛠
#### For all in group
- `/play <song name>` - play song you requested
- `/dplay <song name>` - play song you requested via deezer
- `/splay <song name>` - play song you requested via jio saavn
- `/playlist` - Show now playing list
- `/current` - Show now playing
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/deezer <song name>` - download songs you want quickly via deezer
- `/saavn <song name>` - download songs you want quickly via saavn
- `/video <song name>` - download videos you want quickly


#### Admins only
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/userbotjoin` - invite assistant to your chat
- `/userbotleave` - remove assistant from your chat
- `/admincache` - Refresh admin list

- Inline search is also supported.


## CONTACT ME
- [Owner](https://t.me/Abcdmukakntl)
- [Creator](https://t.me/Abcdmukakntl)

## Credits
- [YZNWA](https://github.com/yznwamusicbot)

