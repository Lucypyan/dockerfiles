# Используем официальный образ OpenJDK
FROM openjdk:11

LABEL author="mama"

# Устанавливаем рабочую директорию внутри контейнера
WORKDIR /app

# Копируем файл Java-игры в контейнер
COPY game.java /app/game.java

# Компилируем Java-игру
RUN javac game.java

# Команда для запуска Java-игры
CMD ["java", "game"]
