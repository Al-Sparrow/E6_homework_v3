pip install -r requirements.txt
Установить docker. Подключить redis.
Запустить redis в одном терминале командой: docker run --rm -p 6379:6379 redis:7
Запустить проект в другом терминале командой: py manage.py runserver