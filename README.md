![logo](https://media2.giphy.com/media/3003MwjfivhWUU55XX/giphy.gif?cid=ecf05e47gap1eok9cx50a80dme14d1zc6n56jogouihyr79r&rid=giphy.gif&ct=g)
## 🚀 Invitation Link

[Link](https://discord.com/api/oauth2/authorize?client_id=443415127048585226&permissions=8&scope=bot)

## 🚀 Getting Started 

```
https://github.com/joaojsrbr/Pathfinder-Bot.git
cd Pathfinder-Bot
npm install
```

After installation finishes you can use `node index.js` to start the bot.

## ⚙️ Configuration

Copy or Rename `config.json.example` to `config.json` and fill out the values:

⚠️ **Note: Never commit or share your token or api keys publicly** ⚠️

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 25,
  "PREFIX": "-",
  "PRUNING": false,
  "LOCALE": "pt_br",
  "STAY_TIME": 90,
  "DEFAULT_VOLUME": 100
}
```

Currently available locales are:
- English (en)
- Arabic (ar)
- Brazilian Portuguese (pt_br)
- Dutch (nl)
- French (fr)
- German (de)
- Italian (it)
- Japanese (ja)
- Korean (ko)
- Polish (pl)
- Russian (ru)
- Simplified Chinese (zh_cn)
- Singaporean Mandarin (zh_sg)
- Spanish (es)
- Swedish (sv)
- Traditional Chinese (zh_tw)
- Thai (th)
- Turkish (tr)
- Vietnamese (vi)

## 📝 Features & Commands

> Note: The default prefix is '-'

* 🎶 Play music from YouTube via url

`-play https://www.youtube.com/watch?v=GLvohMXgcBo`

* 🔎 Play music from YouTube via search query

`-play under the bridge red hot chili peppers`

* 🎶 Play music from Soundcloud via url

`-play https://soundcloud.com/blackhorsebrigade/pearl-jam-alive`

* 🔎 Search and select music to play

`-search Pearl Jam`

Reply with song number or numbers seperated by comma that you wish to play

Examples: `1` or `1,2,3`

* 📃 Play youtube playlists via url

`-playlist https://www.youtube.com/watch?v=YlUKcNNmywk&list=PL5RNCwK3GIO13SR_o57bGJCEmqFAwq82c`

* 🔎 Play youtube playlists via search query

`-playlist linkin park meteora`
* Now Playing (-np)
* Queue system (-queue, -q)
* Loop / Repeat (-loop)
* Shuffle (-shuffle)
* Volume control (-volume, -v)
* Lyrics (-lyrics, -ly)
* Pause (-pause)
* Resume (-resume, -r)
* Skip (-skip, -s)
* Skip to song # in queue (-skipto, -st)
* Move a song in the queue (-move, -mv)
* Remove song # from queue (-remove, -rm)
* Play an mp3 clip (-clip song.mp3) (put the file in sounds folder)
* List all clips (-clips)
* Show ping to Discord API (-ping)
* Show bot uptime (-uptime)
* Toggle pruning of bot messages (-pruning)
* Help (-help, -h)
* Media Controls via Reactions




