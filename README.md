# Xenfire Support

Xenfire Support is a Discord ticket bot powered by Ticket-Bot, an open-source project built with `@discordjs/core`.

![discord ticket bot typescript](https://i.imgur.com/qEzUBOL.png)

## Quick Start

1. Create a Discord application and bot in the [Discord Developer Portal](https://discord.com/developers/applications). Set the bot's display name and avatar there if you want to customize its Discord profile.
2. Create or choose the Discord server where the bot will run. The bot cannot create a Discord server for you. Enable Developer Mode in Discord, then right-click the server and choose **Copy Server ID**.
3. Install [Bun](https://bun.sh/), then install dependencies and generate your local config files:

  ```sh
  bun install
  bun run prepare:config
  ```

4. Put your bot token in `config/.env` as `DISCORD_TOKEN=...`. In `config/config.ts`, set `clientId` to the application ID from **General Information** and `guildId` to the server ID you copied.
5. Invite the bot to that server with the `bot` and `applications.commands` scopes, then start it:

  ```sh
  bun run start
  ```

The bot deploys slash commands to the configured server on startup. Keep `config/.env` private; it is ignored by Git. The sample status and bot application description retain the required Ticket-Bot attribution.

## 📄 Documentation

The documentation is available [here](https://github.com/Sayrix/Ticket-Bot/wiki)

## 💬 Discord

Ask questions and get support on our [Discord server](https://discord.gg/VasYV6MEJy).

## ✨ Contributing

Contributions are welcome! Please read the [contributing guidelines](https://github.com/Sayrix/Ticket-Bot/blob/main/CONTRIBUTING.md) first.

## 👨‍💻 Maintainers
Our current project maintainers:
* [Sayrix](https://github.com/Sayrix)
* [小兽兽/zhiyan114](https://github.com/zhiyan114)

## 💎 Sponsors
Thanks to all our sponsors! 🙏  
You can see all perks here: https://github.com/sponsors/Sayrix
<p align="center">
  <a href="https://cdn.jsdelivr.net/gh/sayrix/sponsors/sponsors.svg">
    <img src='https://raw.githubusercontent.com/Sayrix/sponsors/main/sponsors.svg'/>
  </a>
</p>

## 🎥 Videos  
- Have you made a video about Ticket-Bot? Please share it with us on our [Discord server](https://discord.gg/VasYV6MEJy) to get it listed here!

## Please leave a ⭐ to help the project!

## License
Ticket-Bot is licensed under the GNU Affero General Public License,
version 3 only ("AGPL-3.0-only"). See LICENSE.md for the full license text.

Additional Term under GNU AGPL v3, Section 7(b):

You are required to preserve and display, in a location clearly visible
to end users interacting with the bot (such as bot embeds, the bot's
"Bio" Discord profile, status, or equivalent), a notice that the
software is powered by Ticket-Bot, including a link to the original
project repository or to its website.

This notice must not be removed, obscured, or replaced.