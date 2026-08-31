[EN](../README.md) | RU

## Telegram session importer 📲

Плагин для AyuGram / exteraGram: импорт `.session` файлов в свободный слот аккаунта.

**Версия:** 1.0.0

## 🚀 Quick start

1. Скопируй `telegram_session_importer.plugin` в папку плагинов клиента
2. Включи плагин в настройках
3. Перезапусти клиент

## 📋 Commands

| Команда | Описание |
|---------|----------|
| `.imp` | Импорт (reply на `.session` или путь) |
| `.impui` | Открыть UI импорта |
| `.impdiag` | Диагностика |
| `.impstatus` | Статус последнего импорта |
| `.impslots` | Состояние слотов аккаунтов |

## 🎮 Usage

1. Отправь `.session` в Saved Messages
2. Скачай файл
3. Ответь на него командой `.imp`

Или: `.imp /full/path/to/file.session`  
Если user id неверный: `.imp /path/file.session USER_ID`

После импорта - **полный force-stop** и перезапуск клиента.

## ⚙️ Requirements

- AyuGram / exteraGram `>= 11.12.0`
- Telethon-compatible `.session` (SQLite)
