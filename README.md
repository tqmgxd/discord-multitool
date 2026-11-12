# Multitool - Discord OSINT & Tools

Native C++ desktop app styled like the Ubuntu GNOME Terminal, built with pure Win32 and zero dependencies.

## 🚀 Features
- **Standalone `.exe`**: Statically linked C++ binary (no Python/Node.js required).
- **Quest Completer**: Simulates game processes to finish Discord Quests without downloading games.
- **Username Checker**: Checks Pomelo usernames with rate-limit (`429`) handling and `hits.txt` logging.
- **OSINT & Snowflakes**: Decodes Discord IDs, timestamps, invites, avatars, and webhooks.
- **Terminal UX**: Text selection, copy/paste (`Ctrl+C`/`Ctrl+V`), and `Tab` autocompletion.

## 🛠️ Commands
- **Quests**: `quest list`, `quest start <name>`, `quest status`, `quest stop`
- **Checker**: `check <4c|3l|og|wordlist.txt|name>`, `hits`, `stop`
- **OSINT**: `discord <id>`, `snowflake <id>`, `server <id>`, `invite <code>`, `webhook <url>`
- **System**: `token <val>`, `export [txt|json]`, `clear`, `exit`
