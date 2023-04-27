# BotStatus
Auto-Update Status of Telegram Bots and List as Message. 

A simple, short, mostly customisable GitHub Action to show your bot's status in your GitHub MarkDown file as well as in your Telegram. 

---
### How To Setup?

1. Fill all Variables in `.github/workflows/main.yml`
2. Run Actions.


<details>
  <summary><b>🤫&nbsp;Environment variables</b></summary>
  <br/>

| 🔒 Secret | 🏷 Description | ⚙️ Default | 📇 Example |
| :-: | :-: | :-: | :-: |
| `API_HASH` | Get it from [my.telegram.org](https://my.telegram.org) | `None` | `782xxxx` |
| `APP_ID` | Get it from [my.telegram.org](https://my.telegram.org) | `None` | `a1bbfb767fd59812bxxxxxxxxxxxxxxx` |
| `IDS` | IDs of the Messgage followed with `chat id` | `None` | `-100153418xxxx:3 -100225478xxxx:16` |
| `SESSION` | [![Run on Repl.it](https://replit.com/badge/github/jainamoswal/SessionString)](https://replit.com/@jainamoswal/SessionString) | `None` | `xxxxxxxxxxxxxxxx.....` |
| `BOTS` | Raw link of JSON file of bots. | [🔗 Link 🔗](https://gist.githubusercontent.com/jainamoswal/cc331a3d2a4169ab76885c5a1e076d68/raw/579dc4eabce06bc8d4e4e2192449bf1bf53a8193/bots.json) | [JSON format](/example.json) ║ [Raw link](https://gist.githubusercontent.com/jainamoswal/cc331a3d2a4169ab76885c5a1e076d68/raw/579dc4eabce06bc8d4e4e2192449bf1bf53a8193/bots.json) |


**Format of chat IDs » `chat id`:`message id` 
Eg, `-100123456xxx:1x` where `100123456xxx` is `chat id` and `1x` is `message id`.**
