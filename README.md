# 📅 Tarixdə Bu Gün - Telegram Botu

Bu bot hər gün Wikipedia mənbəsindən "Tarixdə bu gün" başlığı altında tarixi hadisələri göstərir. Bot Python dili ilə yazılıb və Wikipedia səhifələrindən məlumatları `BeautifulSoup` vasitəsilə çəkir.

## 🔧 Xüsusiyyətlər

- `/start` — Bot haqqında məlumat verir.
- `/bugün` — Bugünkü tarixdə baş vermiş hadisələri göstərir.
- Gələcəkdə istənilən tarix üçün axtarış (məs: `/tarix 1 yanvar`) əlavə olunacaq.

## 🧰 İstifadə olunan texnologiyalar

- Python 3
- python-telegram-bot
- requests
- BeautifulSoup4

## 🚀 Quraşdırma və işə salma

1. Layihəni klonla:
    ```bash
    git clone https://github.com/istifadeci/tarixde-bu-gun-bot.git
    cd tarixde-bu-gun-bot
    ```

2. Virtual mühit yarat və aktiv et:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Windows: venv\Scripts\activate
    ```

3. Kitabxanaları quraşdır:
    ```bash
    pip install -r requirements.txt
    ```

4. `.env` faylına bot tokenini əlavə et:
    ```
    TELEGRAM_BOT_TOKEN=buraya_token
    ```

5. Botu işə sal:
    ```bash
    python bot.py
    ```

## 📝 Gələcək planlar

- Tarixə görə sorğu funksiyası
- Şəkilli hadisələr
- Doğum və ölüm məlumatları

## English
# 📅 On This Day - Telegram Bot

This bot fetches and displays historical events from Wikipedia related to today's date. It is built with Python and uses `BeautifulSoup` to scrape data from Wikipedia pages.

## 🔧 Features

- `/start` — Introduction to the bot.
- `/today` — Shows historical events that happened on today’s date.
- More features (like custom date search) will be added soon.

## 🧰 Technologies Used

- Python 3
- python-telegram-bot
- requests
- BeautifulSoup4

## 🚀 Setup and Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/on-this-day-bot.git
    cd on-this-day-bot
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # For Windows: venv\Scripts\activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Create a `.env` file and insert your bot token:
    ```
    TELEGRAM_BOT_TOKEN=your_token_here
    ```

5. Run the bot:
    ```bash
    python bot.py
    ```

## 📝 Future Plans

- Search for any given date
- Add images to events
- Include birth and death information

## Russian

# 📅 Этот День в Истории - Телеграм Бот

Бот показывает исторические события, произошедшие в этот день, используя информацию с Wikipedia. Написан на Python с использованием `BeautifulSoup` для парсинга страниц.

## 🔧 Функции

- `/start` — Информация о боте.
- `/сегодня` — Показывает события, произошедшие сегодня.
- В будущем будет добавлен поиск по дате (например, `/дата 1 января`).

## 🧰 Используемые технологии

- Python 3
- python-telegram-bot
- requests
- BeautifulSoup4

## 🚀 Установка и запуск

1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/вашлогин/bot-on-this-day.git
    cd bot-on-this-day
    ```

2. Создайте виртуальное окружение:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Windows: venv\Scripts\activate
    ```

3. Установите зависимости:
    ```bash
    pip install -r requirements.txt
    ```

4. В `.env` файл добавьте токен бота:
    ```
    TELEGRAM_BOT_TOKEN=ваш_токен
    ```

5. Запустите бота:
    ```bash
    python bot.py
    ```

## 📝 Планы на будущее

- Поиск событий по дате
- Добавление изображений
- Информация о днях рождения и смерти





