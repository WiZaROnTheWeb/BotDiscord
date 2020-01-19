# botDiscord
simple bot
Built with [nodejs](https://nodejs.org/en/) and the [discordjs](https://discord.js.org/#/) library.

### Setup
 - You need `git` and `nodejs` on your system
 - create a `user bot`
    It will have a `bot ID` and a `bot token`.

    You can find all that on the discord website :

    [https://discordapp.com/developers/applications/me](https://discordapp.com/developers/applications/me)


 - Then authorize your bot to your discord with this link :

    `https://discordapp.com/oauth2/authorize?&client_id=BOT_ID&scope=bot`

    (where `BOT_ID` is replaced by your bot id)

 - Find your id by right-clicking yourself and click `copy ID` in the menuq

### Install
```shell
# clone the repo and go into the folder
git clone https://github.com/Misames/BotDiscord.git && cd botDiscord

# install the required modules (discord.js here)
npm install

# start the bot
node bot

```
