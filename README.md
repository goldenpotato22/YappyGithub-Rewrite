# Yappy, the Github Monitor - Rewrite
## Full credit to datitisev for creating the code

[![Online Users in Yappy Discord Server](https://discordapp.com/api/guilds/231548941492027393/embed.png)](https://discord.gg/HHqndMG)
<span class="badge-patreon"><a href="https://www.patreon.com/YappyBots" title="Donate to this project using Patreon"><img src="https://img.shields.io/badge/patreon-donate-yellow.svg" alt="Patreon donate button" /></a></span>

Monitor your github repos by adding this bot to your server, set up a channel for it, and don't miss any events!

### Help

Join our Discord server at https://discord.gg/HHqndMG

### Commands
Prefixes are `G! ` (with space), custom prefix set up, or mention the bot.

__**Util**__:
  - `help` - a help command... yeah :P
  - `invite` - how to invite the bot and set up github events!
  - `clean` - cleans the bot's messages found in the last 100 messages
  - `ping` - uh... ping? pong!
  - `stats` - shows the stats of the bot... what else?

__**Github**__:
  - `issues search <query>` - search issues by any field in the global repo
  - `issue <number>` - gives info about that specific issue in the global repo
  - `pr search <query>` - search pull requests by any field in the global repo
  - `pr <number>` - gives info about that specific pr in the global repo
  - `release <query>` - gives info about a release that matches that query in its tag in the global repo

__**Admin**__:
  - `conf [view]` - views the server's config
  - `conf get <key>` - gets a specific config key in the server's config
  - `conf set <key> [value]` - sets the key to the value, `repo`'s value may be none to disable
  - `init <repo> [private]` - initialize repo events on channel
  - `remove` - remove repo events on channel
