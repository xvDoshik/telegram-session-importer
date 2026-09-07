EN | [RU](docs/README_RU.md)

## Telegram session importer 📲

Plugin for AyuGram / exteraGram: import `.session` files into a free account slot.

**Version:** 1.3.0

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

Works in **any chat**, not only Saved Messages.

1. Download a `.session` file
2. Reply to it with `.imp`

Or attach `.session` and send with caption `.imp`.

Or by path / name:
```
.imp /sdcard/Download/5493225021.session
.imp 5493225021
.imp /path/file.session USER_ID
```

After import - full force-stop and restart the client.

## ⚙️ Requirements

- AyuGram / exteraGram `>= 11.12.0`
- Telethon or Pyrogram `.session` (SQLite)
