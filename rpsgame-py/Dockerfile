# Используем официальный образ Python
FROM python:3

LABEL author="mama"

# Устанавливаем рабочую директорию внутри контейнера
WORKDIR /app

# Копируем файл с игрой в контейнер
COPY RockPaperScissorsGame.py /app/RockPaperScissorsGame.py

# Команда для запуска Python-игры
CMD ["python", "RockPaperScissorsGame.py"]
