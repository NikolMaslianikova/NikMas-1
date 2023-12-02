# NikMas-1
## Інструкція по розгортанню

1. **Крок 1**: Спочатку склонуйте репозиторій на свій локальний комп'ютер:

    ```bash
    git clone https://github.com/NikolMaslianikova/NikMas-1.git
    ```

2. **Крок 2**: Перейдіть до каталогу проекту:

    ```bash
    cd /Users/nikmas/PycharmProjects/PP-1LAB
    ```

3. **Крок 3**: Встановіть залежності проекту (якщо це потрібно):

    ```bash
    poetry install
    ```

4. **Крок 4**: Запустіть сервер або ваш додаток:

    ```bash
    gunicorn -w 4 -b 127.0.0.1:5000 wsgi:app
    ```

    Або:

    ```bash
    waitress-serve --listen=127.0.0.1:5000 wsgi:app
    ```

5. **Крок 5**: Відкрийте веб-браузер та перейдіть за посиланням:

    [http://127.0.0.1:5000](http://127.0.0.1:5000)

Готово! Тепер ваш проект повинен бути розгорнутий та доступний за вказаною адресою.
