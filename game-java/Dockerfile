# Используем базовый образ Java
FROM openjdk:alpine
# Устанавливаем рабочую директорию
WORKDIR /dir/game
# Копируем содержимое текущей директории в контейнер
COPY . /dir/game
# Компилируем Java приложение
RUN javac game.java
# Запускаем приложение при старте контейнера
CMD [ "java" , "game" ]