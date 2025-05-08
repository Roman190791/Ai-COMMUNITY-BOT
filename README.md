
# AI Community Telegram Bot

Цей бот автоматизує модерацію Telegram-групи:

- Привітання нових учасників
- Видалення повідомлень із посиланнями
- Бан користувачів по команді /ban
- Команда /start для запуску

## Запуск локально

```bash
pip install -r requirements.txt
python bot.py
```

## Запуск на Render

1. Підключіть GitHub репозиторій
2. Створіть Web Service
3. Вкажіть команду запуску: `python bot.py`
4. Додайте змінну середовища: `API_TOKEN=your_token`
