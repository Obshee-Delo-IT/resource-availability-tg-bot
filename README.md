# checking_resources_bot

Телеграм-бот создан для проверки доступности интернет-ресурсов

Бот умеет:
- раз в n минут опрашивать список ресурсов (по умолчанию раз в 4 ч);
- анализировать ответ от ресурсов по кодам HTTP;
- сообщать о проблемах ресурсов через сообщение в Telegram по заданным id.
- сообщать об ошибках работы бота по через сообщение в Telegram по заданному id админа.
- логировать свою работу.

Для запуска требуется установить зависимости и создать .env с перечнем параметром:
- TELEGRAM_TOKEN в формате <token>,
- TELEGRAM_CHAT_ID в формате <id_1,id_2,id_n>,
- TELEGRAM_CHAT_ADMIN_ID в формате <id>.

Перечень url указан в коде (bot.py). В будущем будет вынесен в отдельный файл.

Перечень зависимостей - см. requirements.txt.
