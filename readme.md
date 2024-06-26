<img width="20%" src="https://raw.githubusercontent.com/pelican-dev/panel/main/public/pelican.svg" alt="logo">

# Pelican Panel

![Total Downloads](https://img.shields.io/github/downloads/pelican-dev/panel/total?style=flat&label=Total%20Downloads&labelColor=rgba(0%2C%2070%2C%20114%2C%201)&color=rgba(255%2C%20255%2C%20255%2C%201))
![Latest Release](https://img.shields.io/github/v/release/pelican-dev/panel?style=flat&label=Latest%20Release&labelColor=rgba(0%2C%2070%2C%20114%2C%201)&color=rgba(255%2C%20255%2C%20255%2C%201))


Pelican Panel is an open-source, web-based application designed for easy management of game servers.
It offers a user-friendly interface for deploying, configuring, and managing servers, with features like real-time resource monitoring, Docker container isolation, and extensive customization options.
Ideal for both individual gamers and hosting companies, it simplifies server administration without requiring deep technical knowledge.

Fly High, Game On: Pelican's pledge for unrivaled game servers.

## Links

* [Official Discord](https://discord.gg/pelican-panel)
* [Wings](https://github.com/pelican-dev/wings)
* [Official Website](https://pelican.dev/)
* [Getting started](https://pelican.dev/docs/panel/getting-started)
* [FAQ](https://pelican.dev/faq)

## Compatibility
Pelican runs on a wide range of operating systems, so pick whichever you are most comfortable using.

| Operating System | Version | Supported | Notes |
|---|---|---|---|
| Ubuntu | 20.04 |  ⚠️︎ | **No SQLite Support**, Ubuntu 20.04 EoL is April 2025, not recommended |
|  | 22.04 | ✅︎ |  |
|  | 24.04 | ✅︎ | Documentation written assuming Ubuntu 24.04 as the base OS. |
| Rocky Linux | 9 | ✅︎ | |  |
| Debian | 11 | ⚠️ | **No SQLite Support** |
|  | 12 | ✅︎ |  |

> Note: Other OS's, not listed above, might still work.

> SQLite support depends on [libsqlite3-0_3.35+](https://pkgs.org/download/libsqlite3-0) being on the host system. Ubuntu 20.04 & Debian 11 do not meet this requirement.

## Supported Games and Servers

Pelican supports a wide variety of games by utilizing Docker containers to isolate each instance.
This gives you the power to run game servers without bloating machines with a host of additional dependencies.

Some of our popular eggs include but are not limited to:

* [Minecraft](https://github.com/pelican-eggs/minecraft)
  * Paper
  * Sponge
  * Bungeecord
  * Waterfall
* [SteamCMD](https://github.com/pelican-eggs/steamcmd)
  * 7 Days to Die
  * ARK: Survival
  * ARMA
  * Counter Strike
  * DayZ
  * Enshrouded
  * Left 4 Dead
  * Palworld
  * Project Zomboid
  * Sons of the Forest
* [Other Games](https://github.com/pelican-eggs/games)
  * Among Us
  * Factorio
  * GTA
  * Rimworld
  * Terraria
* [Discord Bots](https://github.com/pelican-eggs/chatbots)
  * Redbot
  * JMusicBot
  * SinusBot
  * Dynamica
* [Software](https://github.com/pelican-eggs/software)
* [Programming Languages](https://github.com/pelican-eggs/generic)
  * C#
  * Java
  * Lua
  * Node.js
  * Python
* [Database](https://github.com/pelican-eggs/database)
  * Redis
  * MariaDB
  * PostgreSQL
* [Voice Servers](https://github.com/pelican-eggs/voice)
* [Storage](https://github.com/pelican-eggs/storage)
* [Monitoring](https://github.com/pelican-eggs/monitoring)

Copyright Pelican® 2024
