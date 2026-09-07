[EN](../README.md) | RU

## Telegram session importer 📲

Плагин для AyuGram / exteraGram: импорт `.session` файлов в свободный слот аккаунта.

**Версия:** 1.3.0

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

Работает в **любом чате**.

**Кто-то кинул `.session`:**
1. Скачай файл
2. Reply **`имп`** или просто напиши **`имп`** в этом чате

Команды: `имп`, `.imp`, `imp`, `import`

Или прикрепи `.session` и отправь с подписью `имп`.

Или по пути:
```
.imp /sdcard/Download/5493225021.session
.imp 5493225021
```

После импорта - **полный force-stop** и перезапуск клиента.

## ⚙️ Requirements

- AyuGram / exteraGram `>= 11.12.0`
- Telethon или Pyrogram `.session` (SQLite)
