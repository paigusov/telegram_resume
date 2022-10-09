# Telegram_resume

### paigusov_bot

Простой бот работающий с API внешнего ресурса. Задача бота - присылать рандомные изображения котиков пользователю по запросу.

У API  есть лишь один эндпоинт: 
https://api.thecatapi.com/v1/images/search

### Принцип работы API
Пользователю доступна кнопка "/new_cat".

- при нажатии пользователю присылается новая рандомная картинка с котиком.

### Запуск на ПК

Клонируем проект:

```bash
git clone https://github.com/paigusov/telegram_resume.git
```

или

```bash
git clone git@github.com:paigusov/telegram_resume.git
```

Переходим в папку с ботом.

```bash
cd paigusov_bot
```

Устанавливаем виртуальное окружение

```bash
python -m venv venv
```

Активируем виртуальное окружение

```bash
source venv/Scripts/activate
```

> Для деактивации виртуального окружения выполянем (после работы)
> ```bash
> deactivate
> ```

Устанавливаем зависимости

```bash
pip install -r requirements.txt
```

Создаем файл .env и прописываем токен телеграм-бота

```bash
export PRACTICUM_TOKEN=<PRACTICUM_TOKEN>
export TELEGRAM_TOKEN=<TELEGRAM_TOKEN>
export CHAT_ID=<CHAT_ID>
```

Запускаем бота

```bash
python homework.py
```

Бот будет работать, и каждые 10 минут проверять статус вашей домашней работы.

Автор: [Дмитрий Клепиков](https://github.com/themasterid) :+1:
