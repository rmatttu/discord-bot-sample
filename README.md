# discord-bot-sample
Discord bot sample.

## Install

- [Setting up a bot application | discord.js Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)

## Usage

```bash
cp src/config-default.json src/config.json

# Edit it
vi src/config.json
```

# Memo

## Debug

```js
client.on('debug', console.log);
```

```yml

      - ./bot/:/bot/

    command: "tail  \
          -f \
          /dev/null"
```

- [Optimization and Troubleshooting | Discord.js Guide](https://v12.discordjs.guide/voice/optimisation-and-troubleshooting.html#using-ogg-webm-opus-streams)
