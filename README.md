# telegram_resume

Простой бот, отражающий принцип работы с API внешних ресурсов.


##Запуск на ПК
Клонируем проект:

```json
git clone https://github.com/themasterid/homework_bot.git
или

git clone git@github.com:themasterid/homework_bot.git```

Переходим в папку с ботом.

cd homework_bot
Устанавливаем виртуальное окружение

python -m venv venv
Активируем виртуальное окружение

source venv/Scripts/activate
Для деактивации виртуального окружения выполянем (после работы)

deactivate
Устанавливаем зависимости

pip install -r requirements.txt
В консоле импортируем токены для ЯндексюПрактикум и для Телеграмм:

export PRACTICUM_TOKEN=<PRACTICUM_TOKEN>
export TELEGRAM_TOKEN=<TELEGRAM_TOKEN>
export CHAT_ID=<CHAT_ID>
Запускаем бота

python homework.py
Бот будет работать, и каждые 10 минут проверять статус вашей домашней работы.

