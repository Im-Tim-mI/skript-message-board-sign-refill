# Message Board Sign Refill

**English** | [繁體中文](README.zh-TW.md)

Keeps a “message board” chest full of oak signs: every 60 seconds each empty slot gets 16 signs, so players can always grab one to leave a message.

> This repository has two editions of the same script: **繁體中文 (zh-TW)** is the original used on the author's Traditional Chinese server, and **English** is a full translation (commands, messages and variable names) with the same features.

## Features

- Checks every 60 seconds
- Fills only empty slots - other items stay where they are
- Works with chests and barrels (up to 54 slots)

## Requirements

- [Paper](https://papermc.io/) server (developed on Paper 26.2 / Minecraft 26.2)
- [Skript](https://github.com/SkriptLang/Skript) (developed on 2.16.2)

## Installation

1. Install the plugins listed under [Requirements](#requirements).
2. Download **one** edition:

   | Edition | File(s) |
   |---|---|
   | English | [`en/message-board-sign-refill.sk`](en/message-board-sign-refill.sk) |
   | 繁體中文 (original) | [`zh-TW/留言區寶箱告示板填充.sk`](zh-TW/%E7%95%99%E8%A8%80%E5%8D%80%E5%AF%B6%E7%AE%B1%E5%91%8A%E7%A4%BA%E6%9D%BF%E5%A1%AB%E5%85%85.sk) |

3. Copy the `.sk` file(s) into `plugins/Skript/scripts/` on your server.
4. Run `/sk reload message-board-sign-refill` (use the file name you copied) or restart the server.

> [!IMPORTANT]
> Install **only one** edition. Both editions are the same script in different languages - loading both makes them clash or run twice.

## Commands

This script has no commands - it runs automatically.

## Configuration

- Change `location(-982, 77, -1177, world "world")` to your chest location.
- Change `16 oak sign` for another item or amount.

## License

**MIT + Commons Clause** - see [LICENSE](LICENSE) for the full text.

- ✅ You may use, copy, modify and share this script.
- ✅ You **may** install and run it - including modified versions - on Minecraft servers that charge money or are run for profit.
- ❌ You may **not** sell the script itself or modified versions of it, directly or indirectly, or require payment to obtain its files or source code.

Copyright (c) 2026 廷廷小教室、廷廷的家（Tim945）
