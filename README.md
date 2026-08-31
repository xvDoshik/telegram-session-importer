EN | [RU](docs/README_RU.md)

## Telegram session importer 📲

Plugin for AyuGram / exteraGram: import `.session` files into a free account slot.

**Version:** 1.0.0

## 🚀 Quick start

1. Copy `telegram_session_importer.plugin` to the client plugins folder
2. Enable the plugin in settings
3. Restart the client

## 📋 Commands

| Command | Description |
|---------|----------|
| `.imp` | Import (reply to `.session` or path) |
| `.impui` | Open import UI |
| `.impdiag` | Diagnostics |
| `.impstatus` | Last import status |
| `.impslots` | Account slot state |

## 🎮 Usage

1. Send a `.session` to Saved Messages
2. Download the file
3. Reply with `.imp`

Or: `.imp /full/path/to/file.session`  
If user id is wrong: `.imp /path/file.session USER_ID`

After import - full force-stop and restart the client.

## ⚙️ Requirements

- AyuGram / exteraGram `>= 11.12.0`
- Telethon-compatible `.session` (SQLite)
